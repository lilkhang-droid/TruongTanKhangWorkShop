---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
  


### Mục tiêu tuần 7:

* Củng cố kiến thức chuyên sâu về mô hình bảo mật nhiều lớp tầng mạng (VPC, Security Group, NACL).
* Tiếp cận xu hướng phát triển ứng dụng hiện đại qua kiến trúc không máy chủ (Serverless) với AWS Lambda và API Gateway.
* Làm chủ giải pháp quản trị tên miền toàn cầu (Amazon Route 53) và duy trì nhịp độ làm việc nhóm hiệu quả.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn tập lại kiến thức về AWS Networking và Security đã học trong các module trước <br> - Tìm hiểu thêm về mô hình bảo mật nhiều lớp và cách triển khai trong môi trường Cloud <br> - **Thực hành:** Cấu hình VPC, Security Group và NACL để hiểu rõ hơn về cơ chế bảo mật mạng trên AWS | 06/01/2026   | 06/01/2026      |    |
| 3   | - Tìm hiểu về dịch vụ AWS Lambda và kiến trúc không máy chủ (Serverless) trên AWS <br> - Nghiên cứu quy trình xử lý tự động dữ liệu bằng mô hình Serverless Application <br> - **Thực hành:** Tạo Lambda Function cơ bản và kết nối với các dịch vụ AWS khác như S3 và API Gateway | 06/02/2026   | 06/02/2026      |    |
| 4   | - Học tập chuyên sâu về dịch vụ API Gateway trên AWS <br> - Tìm hiểu cơ chế quản lý request, authentication và monitoring cho hệ thống API <br> - **Thực hành:** Xây dựng API đơn giản kết hợp với AWS Lambda để triển khai mô hình Serverless Application | 06/03/2026   | 06/03/2026      |    |
| 5   | - Nghiên cứu về dịch vụ Amazon Route 53 và cách quản lý hệ thống phân giải tên miền (DNS) trên AWS <br> - Tìm hiểu cách cấu hình Domain, Hosted Zone và các Routing Policy cho hệ thống Web Application <br> - **Thực hành:** Kết nối domain với hệ thống triển khai trên EC2 và kiểm tra khả năng hoạt động | 06/04/2026   | 06/04/2026      |    |
| 6   | - Tổng hợp lại toàn bộ khối lượng kiến thức đám mây đã học trong tuần <br> - Xem lại toàn bộ tài liệu và mô hình lab về Networking, Serverless và DNS trên AWS <br> - Họp nhóm trực tuyến (Online): Đánh giá tiến độ học tập, chia sẻ kinh nghiệm thực hành và định hướng nội dung nghiên cứu cho tuần tiếp theo | 06/05/2026   | 06/05/2026      | Tài liệu Lab cá nhân / Group Meeting |


### Kết quả đạt được tuần 7:

* **Tối ưu hóa bảo mật mạng đa lớp:**
  * Thấu hiểu sâu sắc tư duy thiết kế "Defense in Depth" (Phòng thủ theo chiều sâu) thông qua việc kết hợp chặt chẽ giữa tường lửa có trạng thái (Security Group) và không trạng thái (NACL). Cấu hình thành công phân vùng mạng VPC an toàn, cô lập tốt các tài nguyên quan trọng.

* **Làm chủ nền tảng Serverless cơ bản:**
  * Nắm trọn tư duy kiến trúc Serverless, hiểu cách hệ thống tự động co giãn và tối ưu chi phí (chỉ trả tiền khi code chạy). 
  * Triển khai thành công các hàm xử lý sự kiện dựa trên AWS Lambda, tự động kích hoạt khi có thay đổi dữ liệu trên Amazon S3 và định tuyến luồng xử lý thông qua API Gateway.

* **Triển khai Hệ thống API & Quản trị DNS toàn cầu:**
  * Xây dựng thành công hệ thống RESTful API hoàn chỉnh bằng API Gateway kết hợp Lambda. Nắm rõ cách quản lý luồng Request, cấu hình xác thực (Authentication) và giám sát hiệu năng API.
  * Làm chủ kỹ năng cấu hình DNS trên Amazon Route 53: Tạo lập thành công Hosted Zone, hiểu các chính sách định tuyến (Routing Policies) và trỏ tên miền chính xác về địa chỉ máy chủ EC2 đang hoạt động ổn định.

* **Họp nhóm & Định hướng công nghệ:**
  * Duy trì buổi họp tuần hiệu quả, tổng hợp và giải quyết triệt để các lỗi kỹ thuật phát sinh khi làm Lab cấu hình DNS công cộng và Serverless API. Hoàn tất kế hoạch chuẩn bị bước vào giai đoạn tiếp theo.