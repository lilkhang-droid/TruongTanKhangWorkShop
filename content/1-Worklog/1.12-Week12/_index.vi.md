---
title: "Worklog Tuần 12"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---



### Mục tiêu tuần 12:

* Đóng gói toàn diện và nghiệm thu thực tế mô hình hệ thống Web Application đã triển khai trên AWS.
* Thực hiện chu trình kiểm thử nâng cao (Chức năng, Hiệu năng, Bảo mật) để đảm bảo chất lượng vận hành.
* Hoàn thiện cơ chế giám sát, quản trị log và an toàn dữ liệu cuối kỳ; tổng hợp toàn bộ kho tài liệu bài lab phục vụ báo cáo tốt nghiệp.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn tập và hệ thống hóa lại toàn bộ khối lượng kiến thức AWS chuyên sâu đã tích lũy <br> - Đánh giá tổng quan tính thực tế của kiến trúc hệ thống và các nhóm dịch vụ đã triển khai trong suốt giai đoạn thực tập | 07/06/2026   | 07/06/2026      |   |
| 3   | - Thực hành triển khai phiên bản hoàn chỉnh cuối cùng (Production-ready) của ứng dụng trên đám mây AWS <br> - Kiểm tra và tối ưu liên thông luồng dữ liệu giữa các dịch vụ máy chủ EC2, cơ sở dữ liệu RDS, lưu trữ S3 và các dịch vụ bổ trợ liên quan | 07/07/2026   | 07/07/2026      |   |
| 4   | - Tiến hành quy trình kiểm thử toàn diện hệ thống đám mây bao gồm: Kiểm thử chức năng, Kiểm thử hiệu năng chịu tải và Kiểm thử bảo mật hạ tầng <br> - Ghi nhận chi tiết kết quả kiểm thử và đề xuất các phương án cải thiện hệ thống tối ưu | 07/08/2026   | 07/08/2026      |   |
| 5   | - Thực hành thắt chặt và hoàn thiện hệ thống quản trị, vận hành đám mây an toàn <br> - Sử dụng Amazon CloudWatch (giám sát metrics), AWS CloudTrail (ghi log vết hành vi) và AWS Backup (chuỗi sao lưu tự động) để bảo vệ hệ thống | 07/09/2026   | 07/09/2026      |   |
| 6   | - Tiến hành hoàn thiện toàn bộ hệ thống tài liệu mô tả kỹ thuật của dự án đám mây <br> - Tổng hợp, phân loại một cách hệ thống các bài lab thực hành và chuẩn bị đầy đủ nội dung, biểu đồ cấu trúc phục vụ viết báo cáo tổng kết thực tập | 07/10/2026   | 07/10/2026      | Tài liệu Dự án / Kết quả Thực tập |


### Kết quả đạt được tuần 12:

* **Nghiệm thu hạ tầng ứng dụng chạy thực tế:**
  * Triển khai thành công phiên bản hoàn chỉnh của Web Application. Đảm bảo toàn bộ luồng truyền tải dữ liệu, phân giải tên miền, cân bằng tải và phân chia vùng mạng bảo mật (VPC Subnets) phối hợp vận hành mượt mà, không xảy ra lỗi xung đột cấu hình.

* **Hoàn thành chu trình kiểm thử kỹ thuật chuyên sâu:**
  * Đánh giá thành công khả năng chịu tải của cụm máy chủ EC2 khi lưu lượng truy cập tăng cao. Xác thực tính toàn vẹn dữ liệu tầng RDS và đảm bảo các lớp tường lửa (Security Group, NACL) hoạt động chính xác, ngăn chặn tốt các truy cập trái phép.

* **Làm chủ bộ ba công cụ giám sát và An toàn dữ liệu:**
  * Thiết lập hoàn chỉnh hệ thống quản trị vận hành tự động: CloudWatch giám sát chặt chẽ các chỉ số tài nguyên theo thời gian thực; CloudTrail ghi nhận minh bạch mọi hoạt động cấu hình trên tài khoản; và các kế hoạch AWS Backup được lên lịch tự động giúp hệ thống luôn ở trạng thái sẵn sàng phục hồi khi xảy ra thảm họa (Disaster Recovery).

* **Chuẩn bị sẵn sàng báo cáo tổng kết thực tập cuối kỳ:**
  * Đóng gói thành công kho lưu trữ mã nguồn, tài liệu sơ đồ kiến trúc và chuỗi bài Lab kỹ thuật. Hoàn thiện toàn bộ khung nội dung báo cáo thực tập một cách chuyên nghiệp, sẵn sàng trình hội đồng nhà trường đánh giá kết quả chặng đường thực tập thực chiến trên AWS.