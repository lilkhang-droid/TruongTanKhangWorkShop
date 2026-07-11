---
title: "Blog 1"
date: 2026-07-09
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---


# Hướng dẫn migration sang Amazon Aurora MySQL với "quyền năng" từ Kiro

Bài blog giới thiệu tính năng mới "Amazon Aurora MySQL power" cho Kiro — một công cụ AI tích hợp trực tiếp vào môi trường IDE giúp tự động hóa và đơn giản hóa toàn bộ quy trình dịch chuyển database từ Amazon RDS for MySQL sang Amazon Aurora MySQL qua 4 giai đoạn (Đánh giá, Đồng bộ, Nâng cấp, Chuyển đổi) bằng ngôn ngữ tự nhiên, giúp giảm tối đa thời gian chuẩn bị và đưa downtime khi cutover (chuyển vùng hệ thống) xuống chỉ còn vài chục giây.

Các điểm chính cần nắm:

* **Khái niệm về Kiro Powers:** Là công cụ mở rộng chuyên biệt giúp trợ lý AI của Kiro IDE sở hữu kiến thức chuyên sâu về một công nghệ hoặc dịch vụ cụ thể (nắm vững best-practices, cấu trúc APIs và các cấu hình chuẩn hóa của hệ thống).
* **3 thành phần cốt lõi:** * *MCP servers:* Kết nối trực tiếp để đọc trạng thái tài nguyên AWS và cơ sở dữ liệu (DB) theo thời gian thực.
  * *Steering files:* Nạp sẵn các bộ quy chuẩn và kịch bản thiết kế của chuyên gia.
  * *Validation hooks:* Tự động quét và kiểm tra mọi rủi ro, lỗi tương thích trước khi bấm nút thực thi.
* **Quy trình Migration 4 giai đoạn (Near-Zero Downtime):** bao gồm **Assess** (Đánh giá tính tương thích) → **Migrate** (Đồng bộ dữ liệu ngầm) → **Promote** (Nâng cấp bản sao thành cluster chính) → **Switch** (Chuyển đổi ứng dụng sang Endpoint mới).
* **Yêu cầu phiên bản nguồn:** Instance RDS MySQL hiện tại bắt buộc phải từ phiên bản 5.7.44+ hoặc 8.0.28+ trở lên.
* **Storage Engine:** Chỉ hỗ trợ kiến trúc InnoDB. Nếu hệ thống cơ sở dữ liệu nguồn vẫn có bảng dùng MyISAM thì bắt buộc phải chuyển đổi sang InnoDB trước khi tiến hành dịch chuyển.
* **Cấu hình Backup & Binlog:** Instance nguồn bắt buộc phải kích hoạt tính năng tự động sao lưu (automated backups) với thời gian lưu trữ tối thiểu là 1 ngày để đảm bảo binary logging hoạt động phục vụ việc đồng bộ dữ liệu.
* **Phạm vi triển khai:** Ở phiên bản hiện tại, tính năng chỉ hỗ trợ migration tài nguyên nằm trong cùng một tài khoản AWS và cùng một Region duy nhất.
* **Cơ chế kiểm soát an toàn:** Trợ lý AI chỉ đóng vai trò phân tích, đề xuất giải pháp và chuẩn bị sẵn câu lệnh tự động; hệ thống tuyệt đối không tự ý thay đổi tài nguyên AWS nếu không nhận được sự phê duyệt (approve) từng bước một từ con người.
* **Khả năng tối ưu sau Migration:** Sau khi dịch chuyển lên Aurora thành công, Kiro AI tiếp tục hỗ trợ: tự động khởi chạy read replica theo tải thực tế, cấu hình Aurora Global Database (đa vùng phục vụ dự phòng thảm họa), tối ưu hóa cấu trúc thiết kế schema và tinh chỉnh các câu lệnh SQL.

Tính năng này đặc biệt hữu ích vì nó giới thiệu một giải pháp thực chiến giúp biến quy trình dịch chuyển database (migration) phức tạp và rủi ro từ Amazon RDS sang Aurora thành các bước tự động qua ngôn ngữ tự nhiên; công cụ AI này không chỉ giúp tối thiểu hóa downtime xuống còn vài chục giây mà còn đảm bảo an toàn kỹ thuật nhờ khả năng tự động check lỗi tương thích (binlog, InnoDB) dựa trên các bộ quy chuẩn (best-practices) của chuyên gia AWS.

![image](/images/blog1.png)

Link bài viết: <https://www.facebook.com/groups/awsstudygroupfcj/permalink/2208778813220412/>