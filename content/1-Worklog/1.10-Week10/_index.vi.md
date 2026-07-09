---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
  


### Mục tiêu tuần 10:

* Đánh giá toàn diện tính ổn định và bảo mật của kiến trúc Web Application đã triển khai trên AWS.
* Tối ưu hóa các giải pháp lưu trữ nâng cao (S3), kiến trúc Serverless tích hợp (DynamoDB, Lambda) và cơ chế phục hồi sau sự cố (Disaster Recovery).
* Phân tích các chỉ số hiệu năng hệ thống qua CloudWatch nhằm đưa ra các đề xuất cải thiện và tối ưu hóa tài nguyên.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn tập và kiểm tra lại toàn bộ kiến thức về kiến trúc hệ thống Web Application đã triển khai trên AWS <br> - Đánh giá chuyên sâu sự kết nối và luồng dữ liệu giữa các dịch vụ EC2, RDS, S3, VPC và Load Balancer <br> - Rà soát lại cấu hình hệ thống, quyền truy cập và các thành phần bảo mật nhằm đảm bảo hệ thống vận hành ổn định | 06/22/2026   | 06/22/2026      |    |
| 3   | - Nghiên cứu chuyên sâu về quản lý dữ liệu nâng cao trên AWS <br> - Tìm hiểu các phương pháp tối ưu hóa Amazon S3: Cấu hình Bucket Policy, tính năng Versioning, Lifecycle Rules và kiểm soát phân quyền truy cập dữ liệu chặt chẽ <br> - **Thực hành:** Kiểm tra thực tế khả năng lưu trữ, tính toàn vẹn và bảo vệ dữ liệu trên Cloud | 06/23/2026   | 06/23/2026      |    |
| 4   | - Tìm hiểu chuyên sâu về kiến trúc Serverless nâng cao trên AWS <br> - Nghiên cứu quy trình phối hợp giữa các dịch vụ không máy chủ để tự động hóa quy trình <br> - **Thực hành:** Tích hợp chuỗi dịch vụ AWS Lambda, API Gateway, DynamoDB và S3 để xây dựng ứng dụng xử lý dữ liệu tự động <br> - Đánh giá ưu điểm của mô hình Serverless trong việc giảm thiểu chi phí và đơn giản hóa vận hành | 06/24/2026   | 06/24/2026      |    |
| 5   | - Nghiên cứu chuyên sâu về các cơ chế sao lưu (Backup) và khôi phục dữ liệu (Disaster Recovery) trên AWS <br> - Tìm hiểu cách áp dụng AWS Backup, EC2 Snapshots và RDS Backups <br> - **Thực hành:** Khởi tạo các bản sao lưu tài nguyên hệ thống, giả lập sự cố và kiểm tra toàn diện khả năng phục hồi dữ liệu | 06/25/2026   | 06/25/2026      |    |
| 6   | - Tiến hành quy trình kiểm tra hiệu năng (Performance Testing) và tối ưu hóa hệ thống Cloud đã triển khai <br> - Vận dụng Amazon CloudWatch để theo dõi chi tiết các thông số phần cứng (CPU, Memory, Network) và các chỉ số hoạt động của ứng dụng <br> - Phân tích kết quả giám sát từ biểu đồ và đề xuất các phương án cải thiện hiệu suất | 06/26/2026   | 06/26/2026      |    |


### Kết quả đạt được tuần 10:

* **Tối ưu hóa và thắt chặt bảo mật Web Application:**
  * Kiểm thử thành công khả năng chịu tải và tính liên kết của mô hình ứng dụng đa tầng. Xác thực các lớp bảo mật, đảm bảo cấu hình phân quyền giữa các tài nguyên EC2, RDS và S3 diễn ra an toàn và không có lỗ hổng lộ lọt thông tin.

* **Bảo vệ và quản lý dữ liệu nâng cao trên S3:**
  * Làm chủ kỹ năng quản trị Amazon S3 nâng cao: Triển khai thành công tính năng Versioning để chống ghi đè dữ liệu, thiết lập Bucket Policy hạn chế quyền truy cập công khai và áp dụng Lifecycle Rules giúp tự động chuyển dữ liệu cũ sang các lớp lưu trữ giá rẻ để tối ưu chi phí.

* **Triển khai kiến trúc Serverless nâng cao:**
  * Xây dựng thành công ứng dụng Serverless hoàn chỉnh kết hợp cơ sở dữ liệu NoSQL (Amazon DynamoDB). Hệ thống có khả năng tiếp nhận Request qua API Gateway, kích hoạt Lambda xử lý logic và lưu trữ file vào S3 đồng thời ghi log dữ liệu vào DynamoDB một cách tự động và mượt mà.

* **Nâng cao năng lực Disaster Recovery & Tối ưu hiệu năng:**
  * Triển khai thành công chiến lược sao lưu hợp nhất bằng AWS Backup. Thực hành giả lập kịch bản mất mát tài nguyên và tiến hành khôi phục lại hệ thống trạng thái ổn định từ EC2 Snapshot và RDS Backup thành công.
  * Phân tích sâu các chỉ số thu thập từ CloudWatch, xác định được các điểm nghẽn về hiệu năng (Bottlenecks) của ứng dụng và đưa ra các đề xuất tối ưu hóa cấu hình Instance phù hợp với tải thực tế của doanh nghiệp.