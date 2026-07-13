---
title: "Tuần 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

> **Thời gian:** 27/04/2026 - 01/05/2026 Quản trị cơ sở dữ liệu và di chuyển dữ liệu

---

### Mục tiêu trong tuần

- Làm chủ các loại hình lưu trữ dữ liệu: Phân biệt và thực hành với cả Cơ sở dữ liệu quan hệ (SQL) và phi quan hệ (NoSQL) để phục vụ các bài toán phân tích khác nhau.
- Học cách chuyển đổi và đưa dữ liệu từ môi trường bên ngoài (on-premise) hoặc giữa các hệ thống vào AWS Cloud để sẵn sàng cho việc xử lý.
- Tối ưu hóa truy vấn: Hiểu sâu hơn về các kỹ thuật nâng cao trong SQL để trích xuất dữ liệu hiệu quả hơn.

---

### Nội dung học tập

#### 1. Cơ sở dữ liệu quan hệ (SQL)

- **Database Essentials with Amazon Relational Database Service (RDS):** Học cách khởi tạo, vận hành và mở rộng các cơ sở dữ liệu quan hệ phổ biến (như MySQL, PostgreSQL, SQL Server).
- **Advanced PostgreSQL on AWS (Part 1 & 2):** Thực hành các kỹ thuật nâng cao để tối ưu hóa hiệu suất truy vấn và quản lý các tập dữ liệu phức tạp, điều này cực kỳ hữu ích khi cần tiền xử lý dữ liệu (pre-processing) bằng SQL.

#### 2. Cơ sở dữ liệu NoSQL (dữ liệu phi cấu trúc)

- **NoSQL Database Essentials with Amazon DynamoDB:** Tìm hiểu về dịch vụ cơ sở dữ liệu Key-Value và Document có độ trễ cực thấp. Nắm được các khái niệm cơ bản về cách lưu trữ dữ liệu không cần lược đồ (schema-less).
- **Building Advanced Applications with Amazon DynamoDB:** Thực hành các mô hình thiết kế dữ liệu nâng cao để tối ưu hóa chi phí và tốc độ truy xuất cho các ứng dụng thực tế

#### 3. Di chuyển dữ liệu vào Cloud (Migration)

- **Database Migration with AWS Database Migration Service (DMS):** Thực hành di chuyển dữ liệu một cách an toàn và nhanh chóng từ các nguồn bên ngoài vào AWS với thời gian gián đoạn tối thiểu.
- **Schema Conversion Tool (SCT):** Học cách sử dụng công cụ này để tự động chuyển đổi lược đồ (schema) của cơ sở dữ liệu nguồn sang định dạng tương thích với các dịch vụ mục tiêu trên AWS (ví dụ: chuyển từ Oracle sang Amazon RDS PostgreSQL).

#### 4. Tối ưu hóa hiệu suất truy cập

- **In-Memory Caching with Amazon ElastiCache:** Tìm hiểu cách thiết lập bộ nhớ đệm (Cache) để tăng tốc độ phản hồi của ứng dụng và giảm tải cho cơ sở dữ liệu chính.

#### 5. Quản lý lưu trữ lai (Hybrid Storage)

- **Hybrid Storage with AWS Storage Gateway:** Tìm hiểu cách kết nối môi trường lưu trữ tại chỗ (on-premise) với các dịch vụ lưu trữ đám mây của AWS, giúp việc truyền dẫn dữ liệu nghiên cứu diễn ra liên tục.

---

### Bài học rút ra

- **Hiểu được sự khác biệt giữa cơ sở dữ liệu quan hệ và phi quan hệ:** Hiểu được đặc điểm và trường hợp sử dụng của Amazon RDS và Amazon DynamoDB. Từ đó, biết cách lựa chọn loại cơ sở dữ liệu phù hợp với từng bài toán, tùy thuộc vào cấu trúc dữ liệu, khả năng mở rộng và yêu cầu của hệ thống.
- **Nâng cao kỹ năng xử lý dữ liệu bằng SQL:** Biết cách sử dụng các câu lệnh SQL để lọc, chuyển đổi và tiền xử lý dữ liệu ngay từ giai đoạn truy vấn.
- **Hiểu được quy trình di chuyển dữ liệu trên nền tảng đám mây:** Hiểu được cách dữ liệu được di chuyển và đồng bộ từ cơ sở dữ liệu hiện có lên môi trường Cloud một cách an toàn, hạn chế ảnh hưởng đến hệ thống đang hoạt động và đáp ứng nhu cầu lưu trữ, phân tích dữ liệu của doanh nghiệp.
- **Nhận thức được vai trò của bộ nhớ đệm trong tối ưu hiệu năng hệ thống:** Qua việc tìm hiểu Amazon ElastiCache,hiểu rằng việc sử dụng cơ chế caching giúp tăng tốc độ truy xuất dữ liệu, giảm tải cho cơ sở dữ liệu và cải thiện hiệu suất của các ứng dụng cũng như các hệ thống phân tích và AI/ML trong thực tế.

---

*Nguồn tài liệu chính: [First Cloud Journey - AWS Study Group](https://cloudjourney.awsstudygroup.com/)*
