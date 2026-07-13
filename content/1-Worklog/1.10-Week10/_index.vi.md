---
title: "Tuần 10"
date: 2026-06-15
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

> **Thời gian:** 15/06/2026 - 21/06/2026 Triển khai Query Layer và Dashboard cho hệ thống Data Lakehouse

---

### Mục tiêu trong tuần

- Hoàn thiện Analytics & Visualization Layer cho hệ thống Customer Behavior Analytics trên nền tảng AWS.
- Xây dựng môi trường truy vấn dữ liệu bằng Amazon Athena và kết nối với AWS Glue Data Catalog.
- Phát triển Dashboard trực quan hóa dữ liệu bằng Streamlit và tích hợp với các dịch vụ AWS.
- Triển khai Dashboard lên Amazon EC2, kiểm tra toàn bộ hệ thống và đảm bảo khả năng truy cập từ Internet.

---

### Nội dung công việc

- Thiết lập và cấu hình **Amazon Athena** để truy vấn dữ liệu từ các bảng trong **AWS Glue Data Catalog**.
- Kiểm tra và xác thực dữ liệu tại **Gold Layer** thông qua các câu lệnh SQL, đồng thời đánh giá hiệu suất truy vấn trên dữ liệu định dạng **Apache Parquet**.
- Xây dựng Dashboard bằng **Streamlit** để trực quan hóa dữ liệu phân tích từ hệ thống Data Lakehouse.
- Tích hợp **AWS Wrangler** để kết nối Dashboard với Amazon Athena, cho phép truy vấn trực tiếp dữ liệu từ **Gold Layer**.
- Thiết kế giao diện Dashboard với các chỉ số KPI và biểu đồ phân tích như tổng doanh thu, tổng đơn hàng, tổng khách hàng, giá trị đơn hàng trung bình, doanh thu theo thời gian, quốc gia, thiết bị, phương thức thanh toán và nguồn truy cập.
- Khởi tạo và cấu hình **Amazon EC2**, bao gồm thiết lập **VPC, Public Subnet, Internet Gateway, Route Table** và **Security Group** phục vụ triển khai ứng dụng.
- Cài đặt môi trường Python, các thư viện cần thiết và cấu hình **AWS CLI** cùng thông tin xác thực để Dashboard có thể truy cập các dịch vụ AWS.
- Triển khai ứng dụng Streamlit trên Amazon EC2, cấu hình chạy nền và kiểm tra khả năng truy cập Dashboard thông qua địa chỉ Public IP.
- Kiểm thử toàn bộ luồng dữ liệu từ **Gold Layer → Amazon Athena → Dashboard** nhằm đảm bảo dữ liệu hiển thị chính xác và hệ thống hoạt động ổn định.

---

### Kết quả đạt được

- Hoàn thành **Analytics & Visualization Layer** của hệ thống Customer Behavior Analytics.
Thiết lập thành công môi trường truy vấn dữ liệu bằng Amazon Athena kết hợp với **AWS Glue Data Catalog**.
- Xây dựng hoàn chỉnh Dashboard trực quan hóa dữ liệu bằng **Streamlit**, hiển thị đầy đủ các chỉ số KPI và biểu đồ phân tích.
- Triển khai thành công Dashboard lên **Amazon EC2**, cho phép người dùng truy cập từ Internet thông qua địa chỉ Public IP.
- Xác nhận Dashboard truy vấn dữ liệu chính xác từ **Gold Layer** thông qua **Amazon Athena**, đảm bảo tính nhất quán giữa dữ liệu hiển thị và dữ liệu lưu trữ.
- Hoàn thiện giai đoạn phân tích, trực quan hóa và triển khai hệ thống, tạo nền tảng cho việc kiểm thử và đánh giá toàn bộ pipeline Customer Behavior Analytics trên AWS.

