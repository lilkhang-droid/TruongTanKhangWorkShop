---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
  


### Mục tiêu tuần 6:

* Nghiên cứu chuyên sâu về các giải pháp mở rộng hệ thống (Auto Scaling, ELB), giám sát (CloudWatch, CloudTrail) và bảo mật tầng mạng (Security Groups, NACL).
* Tiếp cận tư duy Tự động hóa hạ tầng (IaC) thông qua CloudFormation và triển khai nhanh với Elastic Beanstalk.
* Thực hành tích hợp chuỗi dịch vụ và họp nhóm tổng kết, đánh giá tiến độ chặng đường học tập.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn tập kiến thức về các dịch vụ Compute và Storage trên AWS <br> - Tìm hiểu chuyên sâu hơn về Amazon EC2, Auto Scaling và Elastic Load Balancer (ELB) để xây dựng hệ thống có độ sẵn sàng cao <br> - **Thực hành:** Triển khai EC2 kết hợp Load Balancer để mô phỏng một hệ thống Web Application cơ bản | 05/25/2026   | 05/25/2026      |    |
| 3   | - Học tập về dịch vụ Monitoring và Logging trên AWS <br> - Tìm hiểu về Amazon CloudWatch, AWS CloudTrail và các công cụ giám sát tài nguyên đám mây <br> - **Thực hành:** Theo dõi hiệu năng EC2, cấu hình các cảnh báo (Alarms) và ghi nhận log hoạt động của hệ thống | 05/26/2026   | 05/26/2026      | [AWS Study Group](https://www.youtube.com/watch?v=NZZRBfCJ2AY&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=224)   |
| 4   | - Nghiên cứu sâu về các giải pháp bảo mật trên AWS <br> - Phân tích chi tiết AWS Security Groups, Network ACLs (NACL) và các nguyên tắc bảo mật hệ thống Cloud bài bản <br> - **Thực hành:** Cấu hình quy tắc kiểm soát truy cập và kiểm tra khả năng bảo mật cho hệ thống đã triển khai | 05/27/2026   | 05/27/2026      |    |
| 5   | - Học tập về dịch vụ triển khai ứng dụng và quản lý tài nguyên tự động trên AWS <br> - Tìm hiểu cơ bản về AWS Elastic Beanstalk và AWS CloudFormation (Infrastructure as Code) <br> - **Thực hành:** Triển khai ứng dụng đơn giản bằng Elastic Beanstalk và tìm hiểu cách tự động hóa hạ tầng qua template CloudFormation | 05/28/2026   | 05/28/2026      |    |
| 6   | - Tổng hợp lại toàn bộ khối lượng kiến thức đã học trong tuần 6 <br> - Xem lại các mô hình lab đã thực hành về EC2, Monitoring, Security và Deployment trên AWS <br> - Họp nhóm trực tuyến (Online): Đánh giá tiến độ học tập cá nhân, chia sẻ kinh nghiệm thực hành và định hướng các nội dung cần tiếp tục nghiên cứu | 05/29/2026   | 05/29/2026      | Tài liệu Lab cá nhân / Group Meeting |


### Kết quả đạt được tuần 6:

* **Thiết kế hệ thống có tính sẵn sàng cao (High Availability):**
  * Nắm vững cơ chế vận hành của Elastic Load Balancer (ELB) và Auto Scaling trong việc tự động điều phối lưu lượng và co giãn tài nguyên theo tải thực tế. Triển khai thành công mô hình Web App cơ bản có khả năng cân bằng tải.

* **Năng lực Giám sát & Quản lý Log:**
  * Hiểu rõ sự khác biệt và phối hợp hiệu quả giữa Amazon CloudWatch (giám sát hiệu năng, chỉ số) và CloudTrail (ghi log vết hoạt động, kiểm toán). Biết cách thiết lập các ngưỡng cảnh báo tự động để chủ động ứng phó khi hệ thống gặp sự cố.

* **Bảo mật tầng mạng chuyên sâu:**
  * Phân biệt rõ ràng cơ chế hoạt động mang tính trạng thái (Stateful) của Security Groups ở cấp độ Instance và phi trạng thái (Stateless) của Network ACLs ở cấp độ Subnet. Thiết lập thành công tường lửa đa lớp vững chắc bảo vệ tài nguyên đám mây.

* **Tiếp cận Tự động hóa hạ tầng (IaC) & Họp nhóm:**
  * Bước đầu làm quen với tư duy quản lý hạ tầng bằng mã (Code) thông qua cấu trúc của AWS CloudFormation và biết cách dùng Elastic Beanstalk để giảm thiểu thời gian đóng gói, triển khai ứng dụng.
  * Duy trì hoạt động họp nhóm hiệu quả, giải quyết các vướng mắc kỹ thuật chung và thống nhất được lộ trình tối ưu cho giai đoạn nghiên cứu kế tiếp.