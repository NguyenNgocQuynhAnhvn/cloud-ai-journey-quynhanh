---
title: "Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

> **Thời gian:** 08/06/2026 - 14/06/2026 Triển khai tầng Ingestion Layer cho hệ thống Data Lakehouse.

---

### Mục tiêu trong tuần

- Triển khai tầng Ingestion Layer cho hệ thống Data Lakehouse nhằm thu thập dữ liệu từ nhiều nguồn khác nhau.
- Xây dựng hai cơ chế tiếp nhận dữ liệu gồm Batch Processing và Streaming Processing để đáp ứng các yêu cầu xử lý dữ liệu định kỳ và dữ liệu thời gian thực.
- Thiết lập và cấu hình các dịch vụ AWS phục vụ quá trình ingest dữ liệu.
- Kiểm tra và đảm bảo dữ liệu được tiếp nhận đầy đủ, chính xác và lưu trữ thành công vào Raw Layer trên Amazon S3.

---

### Nội dung công việc

- Thiết lập **Amazon API Gateway** để tiếp nhận các yêu cầu và dữ liệu từ ứng dụng bên ngoài.
- Phát triển **AWS Lambda** làm nhiệm vụ xử lý dữ liệu đầu vào từ API Gateway và lưu dữ liệu vào hệ thống lưu trữ.
- Cấu hình **Amazon Kinesis Data Firehose** để tiếp nhận luồng dữ liệu Streaming và tự động ghi dữ liệu vào Amazon S3.
- Thiết lập **Amazon EventBridge Scheduler** nhằm tự động kích hoạt quy trình đồng bộ dữ liệu theo lịch định kỳ.
- Xây dựng hàm **AWS Lambda** phục vụ pipeline Batch Processing để đồng bộ dữ liệu từ cơ sở dữ liệu lên Amazon S3.
- Kiểm thử toàn bộ quy trình ingest dữ liệu của cả hai pipeline (Batch Processing và Streaming Processing), đồng thời đánh giá tính ổn định của hệ thống.
- Xác minh dữ liệu được lưu đúng cấu trúc thư mục trong Raw Layer trên Amazon S3.
- Theo dõi và phân tích nhật ký hoạt động thông qua **Amazon CloudWatch Logs** để phát hiện, xử lý lỗi và đánh giá hiệu suất của quá trình tiếp nhận dữ liệu.

---

### Kết quả đạt được

- Hoàn thành việc triển khai tầng Ingestion Layer cho hệ thống Data Lakehouse.
- Xây dựng thành công hai pipeline thu thập dữ liệu theo mô hình Batch Processing và Streaming Processing.
- Thiết lập và tích hợp thành công các dịch vụ **Amazon API Gateway, AWS Lambda, Amazon Kinesis Data Firehose, Amazon EventBridge Scheduler** và **Amazon S3** trong quy trình ingest dữ liệu.
- Dữ liệu được tự động tiếp nhận và lưu trữ thành công vào Raw Layer trên Amazon S3 theo đúng thiết kế kiến trúc.
- Hoàn thành kiểm thử toàn bộ luồng tiếp nhận dữ liệu, xác nhận hệ thống hoạt động ổn định và sẵn sàng cho giai đoạn xây dựng quy trình ETL và xử lý dữ liệu ở các tầng tiếp theo của Data Lakehouse.
