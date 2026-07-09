---
title: "Worklog Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
  


### Mục tiêu tuần 8:

* Nghiên cứu toàn diện về quy trình thiết kế và triển khai kiến trúc ứng dụng nhiều tầng (Three-Tier Architecture) trên môi trường Cloud.
* Tiếp cận xu hướng đóng gói ứng dụng với Docker/Amazon ECS và tự động hóa quy trình phân phối sản phẩm qua chuỗi công cụ CI/CD của AWS.
* Làm chủ các phương pháp giám sát, tối ưu hóa chi phí vận hành tài nguyên hệ thống và củng cố kế hoạch triển khai dự án thực tế cùng nhóm.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn tập lại kiến thức về các dịch vụ AWS đã học trong các module trước <br> - Tìm hiểu quy trình thiết kế và triển khai một hệ thống Web Application toàn diện trên AWS <br> - Phân tích cách phối hợp và kết hợp các dịch vụ cốt lõi như EC2, S3, RDS, Lambda và API Gateway vào một bài toán hệ thống thực tế | 06/08/2026   | 06/08/2026      |    |
| 3   | - Nghiên cứu về mô hình kiến trúc ứng dụng nhiều tầng (Three-Tier Architecture) trên AWS <br> - Tìm hiểu cách phân chia và cô lập các tầng Frontend, Backend và Database trong môi trường Cloud <br> - **Thực hành:** Xây dựng mô hình kiến trúc phân tầng cơ bản sử dụng EC2, RDS trong môi trường VPC an toàn | 06/09/2026   | 06/09/2026      |    |
| 4   | - Học tập về dịch vụ AWS Elastic Container Service (ECS) và khái niệm Container hóa trên Cloud <br> - Tìm hiểu cách sử dụng Docker trong việc đóng gói mã nguồn và triển khai trên hạ tầng AWS <br> - **Thực hành:** Khởi tạo Container đơn giản, đóng gói mã nguồn và triển khai thử nghiệm thành công trên Amazon ECS | 06/10/2026   | 06/10/2026      |    |
| 5   | - Nghiên cứu chuyên sâu về quy trình CI/CD (Tích hợp và phân phối tự động) trên AWS <br> - Tìm hiểu bộ ba dịch vụ cốt lõi: AWS CodePipeline, AWS CodeBuild và AWS CodeDeploy trong tự động hóa quy trình phần mềm <br> - **Thực hành:** Thiết lập và xây dựng một quy trình triển khai tự động (Automated Deployment) hoàn chỉnh cho ứng dụng mẫu | 06/11/2026   | 06/11/2026      |    |
| 6   | - Tìm hiểu về các giải pháp tối ưu hóa chi phí và quản trị tài nguyên thông minh trên AWS <br> - Nghiên cứu bộ công cụ AWS Cost Explorer, AWS Budgets và các chiến lược thực tế giúp cắt giảm chi phí vận hành hệ thống Cloud <br> - Tiến hành kiểm tra, rà soát và đánh giá các tài nguyên AWS đang chạy trên tài khoản cá nhân | 06/12/2026   | 06/12/2026      |    |
| 7   | - Tổng hợp lại toàn bộ chuỗi kiến thức và kỹ năng đám mây đã tích lũy trong tuần 8 <br> - Kiểm tra và tối ưu lại các mô hình bài lab về Kiến trúc hệ thống, Container (ECS), CI/CD và Cost Optimization <br> - Họp nhóm trực tuyến (Online): Đánh giá tiến độ chặng đường học tập, tháo gỡ khó khăn kỹ thuật và thống nhất kế hoạch triển khai dự án thực tế tiếp theo | 06/13/2026   | 06/13/2026      | Tài liệu Lab cá nhân / Group Meeting |


### Kết quả đạt được tuần 8:

* **Tư duy Kiến trúc hệ thống phân tầng (Three-Tier System):**
  * Nắm vững phương pháp thiết kế hệ thống tiêu chuẩn cho doanh nghiệp bằng cách cô lập hoàn toàn tầng dữ liệu (Database) và tầng logic (Backend) trong Subnet riêng biệt, tăng cường tối đa tính bảo mật và khả năng mở rộng.

* **Làm chủ Container hóa & Tự động hóa CI/CD:**
  * Hiểu rõ cơ chế đóng gói ứng dụng bằng Docker và cách quản lý vòng đời container quy mô lớn trên môi trường AWS thông qua Amazon ECS.
  * Xây dựng thành công hệ thống luồng tự động hóa mã nguồn (CI/CD Pipeline). Hiểu rõ cách AWS CodePipeline điều phối mã nguồn từ kho lưu trữ, qua khâu biên dịch (CodeBuild) và tự động cập nhật lên môi trường chạy thực tế (CodeDeploy).

* **Quản lý Tài chính & Tối ưu hóa chi phí Cloud:**
  * Thành thạo kỹ năng sử dụng Cost Explorer để phân tích biểu đồ tiêu thụ tài nguyên và thiết lập các hạn mức cảnh báo dòng tiền tự động với AWS Budgets, tránh các chi phí phát sinh ngoài ý muốn.

* **Hoạt động nhóm và Sẵn sàng cho dự án lớn:**
  * Tổ chức buổi họp nhóm hiệu quả, giải quyết dứt điểm các lỗi phát sinh trong quá trình đóng gói Docker Container và cấu hình IAM Role cho CI/CD Pipeline. 
  * Thống nhất được kiến trúc tổng quan và phân chia công việc rõ ràng cho từng thành viên để chuẩn bị bước vào giai đoạn xây dựng dự án thực tế áp dụng toàn bộ các dịch vụ Cloud đã học.