---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
  


### Mục tiêu tuần 9:

* Hiện thực hóa kiến thức lý thuyết bằng việc trực tiếp triển khai một hệ thống Web Application hoàn chỉnh trên môi trường Cloud.
* Làm chủ kỹ năng cấu hình môi trường mạng an toàn (VPC, Subnets) kết hợp cơ chế tự động mở rộng (Auto Scaling, Load Balancer).
* Tích hợp thành thạo các giải pháp lưu trữ, cơ sở dữ liệu (S3, RDS) và thiết lập giám sát hệ thống (CloudWatch) trước khi nghiệm thu cùng nhóm.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn tập lại kiến thức về kiến trúc hệ thống Cloud và các mô hình triển khai trên AWS <br> - Nghiên cứu chuyên sâu cách xây dựng một hệ thống Web Application hoàn chỉnh sử dụng các dịch vụ AWS cốt lõi (EC2, RDS, S3, VPC và Load Balancer) <br> - Lên kế hoạch thiết kế sơ đồ kiến trúc chi tiết cho dự án thực tế | 06/15/2026   | 06/15/2026      |    |
| 3   | - Tiến hành thực hành triển khai thực tế hệ thống Web Application trên AWS <br> - Cấu hình môi trường mạng cô lập: Thiết lập VPC, các phân vùng Subnets, Internet Gateway và các lớp tường lửa Security Group <br> - Kết nối đồng bộ các thành phần Frontend, Backend và Database trong môi trường Cloud | 06/16/2026   | 06/16/2026      |    |
| 4   | - Nghiên cứu chuyên sâu về cơ chế quản lý và đồng bộ dữ liệu an toàn trên AWS <br> - **Thực hành:** Kết nối ứng dụng trực tiếp với Amazon RDS, cấu hình các thông số Database Instance, thiết lập cơ chế tự động sao lưu (Backup) và kiểm tra toàn diện khả năng truy xuất dữ liệu từ ứng dụng | 06/17/2026   | 06/17/2026      |    |
| 5   | - Tìm hiểu và phân tích sâu về khả năng co giãn linh hoạt và tính sẵn sàng cao (High Availability) của hệ thống hạ tầng AWS <br> - **Thực hành:** Cấu hình Auto Scaling Group kết hợp Elastic Load Balancer để đảm bảo ứng dụng có thể tự động chịu tải khi lưu lượng truy cập đột biến | 06/18/2026   | 06/18/2026      |    |
| 6   | - Nghiên cứu các giải pháp, phương pháp giám sát tài nguyên và tối ưu hóa hiệu năng hệ thống trên AWS <br> - **Thực hành:** Triển khai sử dụng Amazon CloudWatch để theo dõi chỉ số tài nguyên, thiết lập các ngưỡng cảnh báo tự động (Alarms) và phân tích sâu hiệu suất hoạt động của ứng dụng | 06/19/2026   | 06/19/2026      |    |
| 7   | - Tổng hợp lại toàn bộ chuỗi kiến thức và kỹ năng thực tế đã đạt được trong tuần 9 <br> - Rà soát toàn bộ hệ thống đã triển khai, đánh giá khả năng vận hành liên tục của các dịch vụ AWS đã áp dụng <br> - Họp nhóm trực tuyến (Online): Trao đổi kết quả thực hành, đánh giá tiến độ tổng thể của dự án và xác định các điểm cần tối ưu trong tuần tiếp theo | 06/20/2026   | 06/20/2026      | Tài liệu Hệ thống cá nhân / Group Meeting |


### Kết quả đạt được tuần 9:

* **Triển khai hạ tầng Web Application hoàn chỉnh:**
  * Tự tay xây dựng và định hình thành công cấu trúc topo mạng an toàn thông qua việc chia Subnet công khai (Public) cho tầng giao tiếp và Subnet biệt lập (Private) cho tầng dữ liệu, kết nối thông suốt ba thành phần Frontend, Backend và Database trên đám mây.

* **Làm chủ khả năng lưu trữ và Quản trị dữ liệu đám mây:**
  * Cấu hình thành công cơ sở dữ liệu quan hệ Amazon RDS kết nối trực tiếp đến mã nguồn Backend, thiết lập thành công chu kỳ sao lưu định kỳ tự động giúp bảo toàn dữ liệu trước các kịch bản sự cố hệ thống.

* **Hiện thực hóa kiến trúc có tính sẵn sàng cao (High Availability):**
  * Triển khai tích hợp thành công bộ đôi Elastic Load Balancer và Auto Scaling Group. Hệ thống hoạt động đúng kịch bản thiết kế: Tự động khởi chạy thêm các EC2 Instance khi CPU vượt ngưỡng và phân phối tải đều đặn qua các vùng độc lập (Availability Zones).

* **Nâng cao năng lực Giám sát & Quản lý vận hành nhóm:**
  * Vận dụng thành thạo CloudWatch để thiết lập bảng theo dõi trực quan (Dashboard), cấu hình thành công hệ thống tự động gửi cảnh báo khi phát hiện bất thường về hiệu năng.
  * Buổi họp nhóm diễn ra hiệu quả, đánh giá chất lượng sản phẩm Web App đã chạy thực tế, tháo gỡ các lỗi cấu hình Route Table tầng mạng và phân công chi tiết công việc chuẩn bị cho giai đoạn nghiệm thu.