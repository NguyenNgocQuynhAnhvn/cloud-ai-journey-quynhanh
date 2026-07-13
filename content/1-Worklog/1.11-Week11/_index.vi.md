---
title: "Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

> **Thời gian:** 29/06/2026 - 05/07/2026 Hoàn thiện và kiểm thử hệ thống Customer Behavior Analytics End-to-End

---

### Mục tiêu trong tuần

- Hoàn thiện việc tích hợp toàn bộ các thành phần của hệ thống Customer Behavior Analytics trên nền tảng AWS.
- Kiểm thử quy trình xử lý dữ liệu xuyên suốt từ nguồn dữ liệu đến Dashboard theo mô hình Data Lakehouse.
- Đánh giá tính chính xác, hiệu năng và độ ổn định của hệ thống trong các kịch bản Batch Processing và Streaming Processing.
- Hoàn thiện kiến trúc End-to-End và chuẩn bị tài liệu phục vụ báo cáo, nghiệm thu và trình bày kết quả dự án.

---

### Nội dung công việc

- Tích hợp toàn bộ các thành phần của hệ thống, bao gồm **Ingestion Layer**, **Data Processing Layer**, **Query Layer** và **Dashboard**.
- Kiểm thử toàn bộ pipeline xử lý dữ liệu từ nguồn dữ liệu qua các tầng **Raw**, **Bronze**, **Silver** và **Gold**, sau đó truy vấn bằng **Amazon Athena** và hiển thị trên Dashboard.
- Thực hiện nhiều lần chạy thử quy trình ETL và các luồng **Batch Processing**, **Streaming Processing** để đánh giá tính ổn định của hệ thống.
- Kiểm tra dữ liệu tại từng tầng của kiến trúc Medallion nhằm đảm bảo dữ liệu được xử lý đầy đủ, chính xác và nhất quán.
- Đối chiếu kết quả truy vấn trên **Amazon Athena** với dữ liệu hiển thị trên Dashboard để xác nhận tính đồng nhất của dữ liệu.
- Kiểm tra khả năng cập nhật dữ liệu khi phát sinh dữ liệu mới và xác minh Dashboard phản ánh đúng các thay đổi sau quá trình xử lý.
- Hoàn thiện sơ đồ kiến trúc tổng thể, tài liệu kỹ thuật và quy trình triển khai phục vụ báo cáo và thuyết trình.

---

### Kết quả đạt được

- Hoàn thành việc tích hợp toàn bộ hệ thống Customer Behavior Analytics theo kiến trúc Data Lakehouse.
- Xác nhận dữ liệu được xử lý xuyên suốt từ nguồn dữ liệu đến Dashboard theo đúng quy trình thiết kế.
- Kiểm chứng tính chính xác và nhất quán giữa dữ liệu lưu trữ, kết quả truy vấn trên Amazon Athena và dữ liệu hiển thị trên Dashboard.
- Đảm bảo hệ thống hoạt động ổn định đối với cả hai hình thức xử lý **Batch Processing** và **Streaming Processing**.
- Hoàn thiện phiên bản End-to-End của hệ thống, sẵn sàng phục vụ quá trình đánh giá, nghiệm thu và trình bày kết quả dự án.
