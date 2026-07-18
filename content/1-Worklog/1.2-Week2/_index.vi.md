---
title: "Tuần 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---


**Mục tiêu trong tuần**

- Làm chủ các loại hình lưu trữ dữ liệu: Phân biệt và thực hành với cả Cơ sở dữ liệu quan hệ (SQL) và phi quan hệ (NoSQL) để phục vụ các bài toán phân tích khác nhau.
- Học cách chuyển đổi và đưa dữ liệu từ môi trường bên ngoài (on-premise) hoặc giữa các hệ thống vào AWS Cloud để sẵn sàng cho việc xử lý.
- Tối ưu hóa truy vấn: Hiểu sâu hơn về các kỹ thuật nâng cao trong SQL để trích xuất dữ liệu hiệu quả hơn.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Nghiên cứu và thực hành khởi tạo cơ sở dữ liệu quan hệ đầu tiên với Amazon Relational Database Service (RDS), tìm hiểu các tính năng quản lý tự động như sao lưu (Backups), nâng cấp phiên bản và cấu hình khả năng sẵn sàng cao với Multi-AZ. Thực hiện thiết lập Security Groups để kiểm soát quyền truy cập và kết nối thử nghiệm từ máy chủ EC2 hoặc máy trạm đến database engine nhằm chuẩn bị môi trường cho các bài thực hành phân tích. | 27/4 |
| Thứ Ba | Nghiên cứu và thực hành khởi tạo, vận hành cơ sở dữ liệu quan hệ thông qua Amazon Relational Database Service (RDS), nắm vững cách quản lý các DB engine phổ biến như MySQL hoặc PostgreSQL trên nền tảng Cloud. Đi sâu vào học phần Advanced PostgreSQL on AWS (Part 1 & 2) để thực hành các kỹ thuật tối ưu hóa truy vấn nâng cao và xử lý các tập dữ liệu phức tạp, phục vụ cho việc tiền xử lý dữ liệu (pre-processing)| 28/4 |
| Thứ 4 | Tìm hiểu và thực hành với cơ sở dữ liệu phi quan hệ qua NoSQL Database Essentials với Amazon DynamoDB, xây dựng các bảng dữ liệu có cấu trúc linh hoạt (schema-less) và khả năng mở rộng quy mô lớn. Thực hiện bài Lab Building Advanced Applications với Amazon DynamoDB để nắm vững cách thiết kế mô hình dữ liệu tối ưu cho các bài toán Big Data cần độ trễ cực thấp. | 29/4 |
| Thứ Năm | Thực hành quy trình di chuyển dữ liệu bằng dịch vụ AWS Database Migration Service (DMS) kết hợp với công cụ Schema Conversion Tool (SCT). Nghiên cứu cách tự động chuyển đổi lược đồ (schema) của cơ sở dữ liệu nguồn và thiết lập đường truyền đồng bộ dữ liệu từ môi trường bên ngoài vào AWS một cách an toàn và liên tục. | 30/4 |
| Thứ 6 | Triển khai giải pháp tăng tốc truy xuất dữ liệu bằng cơ chế In-memory caching với Amazon ElastiCache. Đồng thời, nghiên cứu giải pháp lưu trữ lai thông qua AWS Storage Gateway để thiết lập kết nối dữ liệu liền mạch giữa hạ tầng tại chỗ (on-premise) và các dịch vụ lưu trữ đám mây của AWS. | 1/5 |

**Kết quả đạt được trong tuần là gì:**
- **Thứ Hai:**
  - Kết quả đạt được: Triển khai thành công một instance database (MySQL/PostgreSQL) hoàn chỉnh trên đám mây. Thiết lập được kết nối an toàn và nắm vững bảng điều khiển quản trị RDS.
  - Bài học: Việc sử dụng một dịch vụ được quản lý (Managed Service) so với việc tự cài đặt database trên máy chủ ảo EC2 giúp giảm bớt gánh nặng quản trị hạ tầng cho người làm. 
- **Thứ Ba:**
  - Kết quả đạt được: Khởi tạo thành công một Instance RDS PostgreSQL; thực hiện các truy vấn SQL phức tạp với hiệu năng được tối ưu hóa.
  - Bài học: SQL nâng cao giúp làm sạch và xử lý dữ liệu ngay từ cơ sở dữ liệu, giảm khối lượng xử lý bằng Python hoặc R. 
- **Thứ Tư:**
  - Kết quả đạt được: Thiết lập thành công một bảng DynamoDB, thực hành truy xuất dữ liệu Key-Value thành công với tốc độ phản hồi nhanh.
  - Bài học: NoSQL là lựa chọn phù hợp để lưu trữ dữ liệu phi cấu trúc và xử lý khối lượng dữ liệu lớn với tốc độ đọc/ghi cao mà cơ sở dữ liệu quan hệ khó đáp ứng.
- **Thứ Năm:**
  - Kết quả đạt được: Hoàn thành mô phỏng việc di chuyển một cơ sở dữ liệu thực tế lên Cloud với thời gian gián đoạn tối thiểu.
  - Bài học: Hiểu được lợi ích của các công cụ tự động hóa như AWS SCT trong việc giảm sai sót và tiết kiệm thời gian khi chuyển đổi cơ sở dữ liệu. 
- **Thứ Sáu:**
  - Kết quả đạt được: Tích hợp thành công lớp Caching vào hệ thống để giảm tải cho database chính; cấu hình Gateway để đồng bộ dữ liệu cục bộ lên S3 tự động.
  - Bài học: Tối ưu hóa tốc độ cung cấp dữ liệu giúp phản hồi kết quả phân tích theo thời gian thực một cách mượt mà.



