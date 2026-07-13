---
title: "Tuần 9"
date: 2026-06-22
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

> **Thời gian** 22/06/2026 - 28/06/2026 Triển khai Bronze Layer, Silver Layer, Gold Layer trong kiến trúc Medallion Data Lakehouse.

---

### Mục tiêu trong tuần

- Triển khai Data Processing Layer theo kiến trúc Medallion Data Lakehouse.
- Xây dựng các quy trình ETL bằng AWS Glue để xử lý dữ liệu qua ba tầng Bronze, Silver và Gold.
- Chuẩn hóa, làm sạch và tổng hợp dữ liệu nhằm phục vụ phân tích và trực quan hóa.
- Tổ chức dữ liệu theo định dạng tối ưu, đồng thời đăng ký các bảng dữ liệu vào AWS Glue Data Catalog để hỗ trợ truy vấn bằng Amazon Athena.

---

### Nội dung công việc

- Xây dựng hệ thống **AWS Glue ETL Jobs** để xử lý dữ liệu xuyên suốt các tầng **Raw → Bronze → Silver → Gold**.
Triển khai **Bronze Layer** bằng cách chuyển đổi dữ liệu từ định dạng CSV sang **Apache Parquet**, tự động suy luận kiểu dữ liệu (Schema Inference) và tổ chức dữ liệu theo từng bảng trên **Amazon S3**.
- Triển khai **Silver Layer** nhằm làm sạch và chuẩn hóa dữ liệu thông qua việc loại bỏ bản ghi trùng lặp, chuẩn hóa tên cột, xử lý dữ liệu chuỗi, chuẩn hóa định dạng thời gian và kiểm tra tính nhất quán của kiểu dữ liệu.
- Triển khai **Gold Layer** để xây dựng các bảng dữ liệu phân tích phục vụ nghiệp vụ, bao gồm **Dashboard Summary, Daily Revenue, Event Summary, Country Revenue, Device Summary, Payment Summary** và **Source Summary**.
- Thực hiện các phép tổng hợp dữ liệu như thống kê số lượng khách hàng, số lượng đơn hàng, tổng doanh thu, giá trị đơn hàng trung bình và doanh thu theo quốc gia, thiết bị, phương thức thanh toán và nguồn truy cập.
- Lưu toàn bộ dữ liệu sau xử lý dưới định dạng **Apache Parquet** trên **Amazon S3** nhằm tối ưu dung lượng lưu trữ và hiệu suất truy vấn.
- Đăng ký các bảng dữ liệu của Gold Layer vào AWS Glue Data Catalog để hỗ trợ truy vấn bằng Amazon Athena.
Kiểm tra toàn bộ quy trình ETL, xác nhận dữ liệu được xử lý và lưu trữ thành công ở từng tầng của kiến trúc Medallion.

---

### Kết quả đạt được

- Hoàn thành triển khai **Data Processing Layer** theo mô hình Medallion Data Lakehouse.
Xây dựng thành công các **quy trình ETL tự động** bằng AWS Glue cho toàn bộ luồng xử lý dữ liệu từ **Raw → Bronze → Silver → Gold**.
- Chuẩn hóa, làm sạch và tổng hợp dữ liệu thành công, đảm bảo chất lượng dữ liệu phục vụ phân tích.
Hoàn thiện ba tầng Bronze, Silver và Gold với dữ liệu được lưu trữ dưới định dạng **Apache Parquet** trên **Amazon S3**.
- Đăng ký thành công các bảng dữ liệu phân tích vào AWS Glue Data Catalog, sẵn sàng cho việc truy vấn bằng **Amazon Athena**.
- Hoàn thiện nền tảng dữ liệu phục vụ xây dựng Dashboard và các bước phân tích dữ liệu ở giai đoạn tiếp theo.

