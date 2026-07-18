---
title: "Tuần 9"
date: 2026-06-22
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

**Mục tiêu trong tuần**

- Triển khai Data Processing Layer theo kiến trúc Medallion Data Lakehouse.
- Xây dựng các quy trình ETL bằng AWS Glue để xử lý dữ liệu qua ba tầng Bronze, Silver và Gold.
- Chuẩn hóa, làm sạch và tổng hợp dữ liệu nhằm phục vụ phân tích và trực quan hóa.
- Tổ chức dữ liệu theo định dạng tối ưu, đồng thời đăng ký các bảng dữ liệu vào AWS Glue Data Catalog để hỗ trợ truy vấn bằng Amazon Athena.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Xây dựng AWS Glue ETL Jobs cho tầng Bronze Layer, chuyển đổi dữ liệu từ định dạng CSV sang Apache Parquet, tự động suy luận Schema và lưu dữ liệu theo từng bảng trên Amazon S3. | 15/6 |
| Thứ Ba | Triển khai Silver Layer, thực hiện làm sạch và chuẩn hóa dữ liệu thông qua việc loại bỏ dữ liệu trùng lặp, chuẩn hóa tên cột, xử lý dữ liệu chuỗi, chuẩn hóa định dạng thời gian và kiểm tra tính nhất quán của kiểu dữ liệu. | 16/6 |
| Thứ Tư | Xây dựng Gold Layer, thực hiện tổng hợp dữ liệu để tạo các bảng phân tích gồm Dashboard Summary, Daily Revenue, Event Summary, Country Revenue, Device Summary, Payment Summary và Source Summary. | 17/6 |
| Thứ Năm | Lưu toàn bộ dữ liệu sau xử lý dưới định dạng Apache Parquet trên Amazon S3. Đăng ký các bảng dữ liệu của Gold Layer vào AWS Glue Data Catalog và kiểm tra khả năng truy vấn bằng Amazon Athena. | 18/6 |
| Thứ Sáu | Kiểm thử toàn bộ quy trình ETL từ Raw → Bronze → Silver → Gold, xác nhận dữ liệu được xử lý chính xác ở từng tầng, đánh giá hiệu suất và hoàn thiện tài liệu của Data Processing Layer. | 19/6 |

**Kết quả đạt được trong tuần là gì:**

- **Thứ Hai:**
  - **Kết quả đạt được:** Hoàn thành triển khai Bronze Layer bằng AWS Glue ETL, chuyển đổi thành công dữ liệu từ CSV sang Apache Parquet và lưu trữ trên Amazon S3 theo đúng cấu trúc thiết kế.
  - **Bài học:** Chuyển đổi sang định dạng Apache Parquet giúp giảm dung lượng lưu trữ, tăng tốc độ đọc dữ liệu và tối ưu hiệu suất cho các bước xử lý tiếp theo.

- **Thứ Ba:**
  - **Kết quả đạt được:** Hoàn thành Silver Layer với dữ liệu được làm sạch, chuẩn hóa và đảm bảo tính nhất quán trước khi đưa vào phân tích.
  - **Bài học:** Chất lượng dữ liệu quyết định chất lượng kết quả phân tích, vì vậy bước làm sạch và chuẩn hóa đóng vai trò rất quan trọng trong quy trình ETL.

- **Thứ Tư:**
  - **Kết quả đạt được:** Xây dựng thành công Gold Layer với các bảng dữ liệu tổng hợp phục vụ Dashboard và phân tích nghiệp vụ.
  - **Bài học:** Việc tổng hợp dữ liệu theo từng mục đích sử dụng giúp giảm đáng kể thời gian truy vấn, đồng thời hỗ trợ trực quan hóa dữ liệu một cách hiệu quả.

- **Thứ Năm:**
  - **Kết quả đạt được:** Đăng ký thành công các bảng dữ liệu của Gold Layer vào AWS Glue Data Catalog và sẵn sàng cho việc truy vấn bằng Amazon Athena.
  - **Bài học:** Glue Data Catalog đóng vai trò như một kho siêu dữ liệu (Metadata Repository), giúp Athena và các dịch vụ phân tích dễ dàng tìm kiếm và truy cập dữ liệu.

- **Thứ Sáu:**
  - **Kết quả đạt được:** Kiểm thử thành công toàn bộ pipeline ETL từ Raw đến Gold, xác nhận dữ liệu được xử lý chính xác và sẵn sàng phục vụ xây dựng Dashboard.
  - **Bài học:** Kiểm thử toàn bộ quy trình ETL giúp đảm bảo tính chính xác, tính toàn vẹn và độ tin cậy của dữ liệu trước khi đưa vào khai thác và phân tích.

