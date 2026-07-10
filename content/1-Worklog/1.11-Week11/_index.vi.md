---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---



### Mục tiêu tuần 11:

* Đóng gói tài liệu kiến trúc hệ thống và chuyển đổi mô hình quản trị hạ tầng sang dạng mã nguồn (Infrastructure as Code) với CloudFormation.
* Tiếp cận và làm chủ giải pháp điều phối Container quy mô lớn với hạ tầng Amazon EKS (Kubernetes).
* Tối ưu hóa bài toán chi phí, hiệu năng phần cứng và tổng hợp toàn bộ kết quả để chuẩn bị nội dung báo cáo tổng kết thực tập.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn tập lại toàn bộ kiến thức về triển khai hạ tầng trên AWS <br> - Kiểm tra lại kiến trúc Web Application đã xây dựng, đánh giá khả năng mở rộng, tính sẵn sàng cao và mức độ bảo mật của hệ thống <br> - Hoàn thiện tài liệu mô tả kiến trúc triển khai trên AWS | 06/29/2026   | 06/29/2026      |   |
| 3   | - Nghiên cứu về Infrastructure as Code (IaC) trên AWS <br> - Tìm hiểu cách sử dụng AWS CloudFormation để tự động hóa việc triển khai hạ tầng <br> - **Thực hành:** Xây dựng Template CloudFormation để triển khai EC2, VPC và Security Group | 06/30/2026   | 06/30/2026      |   |
| 4   | - Tìm hiểu về dịch vụ Amazon Elastic Kubernetes Service (EKS) <br> - Nghiên cứu kiến trúc Kubernetes trên AWS, cách quản lý Cluster, Node Group và triển khai Container Application trong môi trường Kubernetes | 07/01/2026   | 07/01/2026      |   |
| 5   | - **Thực hành nâng cao:** Triển khai ứng dụng Container trên Kubernetes hoặc EKS <br> - Tìm hiểu cách quản lý Pod, Deployment và Service <br> - Kiểm tra khả năng mở rộng và cập nhật ứng dụng thông qua Kubernetes | 07/02/2026   | 07/02/2026      |   |
| 6   | - Nghiên cứu các phương pháp tối ưu hiệu năng và chi phí khi vận hành hệ thống trên AWS <br> - **Thực hành:** Sử dụng CloudWatch và Cost Explorer để phân tích tài nguyên đang sử dụng, đề xuất phương án tối ưu hiệu suất và giảm chi phí | 07/03/2026   | 07/03/2026      |   |
| 7   | - Tổng hợp toàn bộ kiến thức tuần 11 <br> - Kiểm tra lại các bài lab về CloudFormation, Kubernetes, Monitoring và Cost Optimization <br> - Họp nhóm online: Đánh giá kết quả thực hành, chia sẻ kinh nghiệm triển khai dự án và chuẩn bị nội dung báo cáo tổng kết thực tập | 07/04/2026   | 07/04/2026      | Tài liệu Hệ thống / Group Meeting |


### Kết quả đạt được tuần 11:

* **Chuẩn hóa tài liệu & Tự động hóa IaC:**
  * Hoàn thành xuất sắc tài liệu kỹ thuật chi tiết cho kiến trúc Web Application. Chuyển đổi thành công hạ tầng thủ công sang Infrastructure as Code (IaC) thông qua việc tự tay viết và khởi chạy Template CloudFormation (VPC, Security Group, EC2).

* **Làm chủ điều phối Container với Amazon EKS:**
  * Nắm vững kiến trúc lõi của Kubernetes trên AWS đám mây (Cluster, Control Plane, Node Groups). 
  * Cấu hình thành công các tệp tin manifest để quản trị vòng đời Pod, thiết lập kết nối mạng nội bộ qua Service và thực hiện cập nhật phiên bản ứng dụng không gián đoạn (Rolling Update).

* **Quản trị tài chính và Tối ưu phần cứng:**
  * Vận dụng tốt số liệu phân tích từ bộ đôi CloudWatch và Cost Explorer để phát hiện phần cứng dư thừa, lập báo cáo Rightsizing giúp cắt giảm đáng kể chi phí tiêu thụ tài nguyên hàng tháng.

* **Hoàn thiện chặng đường thực tập:**
  * Buổi họp nhóm diễn ra hiệu quả, xử lý triệt để lỗi cấu hình file YAML và đồng bộ tiến độ cả đội. Tổng hợp toàn bộ hệ thống bài lab, tạo nền tảng dữ liệu vững chắc để xây dựng báo cáo tổng kết thực tập cuối kỳ một cách bài bản.