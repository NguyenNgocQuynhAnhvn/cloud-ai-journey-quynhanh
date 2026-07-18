---
title: "Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---


**Mục tiêu trong tuần**

- Triển khai tầng Ingestion Layer cho hệ thống Data Lakehouse nhằm thu thập dữ liệu từ nhiều nguồn khác nhau.
- Xây dựng hai cơ chế tiếp nhận dữ liệu gồm Batch Processing và Streaming Processing để đáp ứng các yêu cầu xử lý dữ liệu định kỳ và dữ liệu thời gian thực.
- Thiết lập và cấu hình các dịch vụ AWS phục vụ quá trình ingest dữ liệu.
- Kiểm tra và đảm bảo dữ liệu được tiếp nhận đầy đủ, chính xác và lưu trữ thành công vào Raw Layer trên Amazon S3.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Thiết lập Amazon API Gateway để tiếp nhận yêu cầu từ ứng dụng bên ngoài. Xây dựng hàm AWS Lambda xử lý dữ liệu đầu vào và lưu dữ liệu vào Amazon S3. | 8/6 |
| Thứ Ba | Cấu hình Amazon Kinesis Data Firehose để tiếp nhận luồng dữ liệu Streaming và tự động ghi dữ liệu vào Raw Layer trên Amazon S3. Kiểm thử luồng Streaming Processing. | 9/6 |
| Thứ Tư | Thiết lập Amazon EventBridge Scheduler để tự động kích hoạt quy trình đồng bộ dữ liệu theo lịch. Xây dựng hàm AWS Lambda phục vụ pipeline Batch Processing đồng bộ dữ liệu từ cơ sở dữ liệu lên Amazon S3. | 10/6 |
| Thứ Năm | Tích hợp toàn bộ các thành phần của Ingestion Layer, kiểm thử hai pipeline Batch Processing và Streaming Processing, đồng thời xác minh dữ liệu được lưu đúng cấu trúc trong Raw Layer trên Amazon S3. | 11/6 |
| Thứ Sáu | Theo dõi hoạt động của hệ thống bằng Amazon CloudWatch Logs, phân tích nhật ký, xử lý lỗi phát sinh và đánh giá hiệu suất của quá trình ingest dữ liệu. Hoàn thiện tài liệu triển khai Ingestion Layer. | 12/6 |

**Kết quả đạt được trong tuần là gì:**

- **Thứ Hai:**
  - **Kết quả đạt được:** Hoàn thành cấu hình Amazon API Gateway và triển khai AWS Lambda tiếp nhận dữ liệu từ API, lưu dữ liệu thành công lên Amazon S3.
  - **Bài học:** API Gateway kết hợp với Lambda giúp xây dựng các API serverless linh hoạt, dễ mở rộng và giảm đáng kể chi phí vận hành so với mô hình máy chủ truyền thống.

- **Thứ Ba:**
  - **Kết quả đạt được:** Cấu hình thành công Amazon Kinesis Data Firehose, dữ liệu Streaming được tự động ghi vào Raw Layer trên Amazon S3 theo đúng thiết kế.
  - **Bài học:** Kinesis Data Firehose đơn giản hóa việc thu thập dữ liệu thời gian thực, giúp dữ liệu được truyền liên tục mà không cần tự xây dựng cơ chế ghi dữ liệu phức tạp.

- **Thứ Tư:**
  - **Kết quả đạt được:** Hoàn thành pipeline Batch Processing sử dụng Amazon EventBridge Scheduler và AWS Lambda để tự động đồng bộ dữ liệu từ cơ sở dữ liệu lên Amazon S3 theo lịch định kỳ.
  - **Bài học:** Việc tự động hóa quy trình Batch Processing giúp giảm thao tác thủ công, đảm bảo dữ liệu luôn được cập nhật đầy đủ và đúng thời điểm.

- **Thứ Năm:**
  - **Kết quả đạt được:** Tích hợp thành công hai pipeline Batch Processing và Streaming Processing, xác nhận dữ liệu được lưu đúng cấu trúc thư mục trong Raw Layer trên Amazon S3.
  - **Bài học:** Kiểm thử toàn bộ pipeline giúp phát hiện sớm các lỗi tích hợp giữa các dịch vụ AWS, đảm bảo hệ thống hoạt động ổn định trước khi triển khai các bước xử lý dữ liệu tiếp theo.

- **Thứ Sáu:**
  - **Kết quả đạt được:** Theo dõi và phân tích nhật ký hệ thống bằng Amazon CloudWatch Logs, xử lý các lỗi phát sinh và đánh giá hiệu suất của quá trình ingest dữ liệu. Hoàn thiện tài liệu triển khai Ingestion Layer.
  - **Bài học:** CloudWatch Logs là công cụ quan trọng giúp giám sát hệ thống serverless, hỗ trợ nhanh chóng trong việc phát hiện lỗi, tối ưu hiệu năng và nâng cao độ tin cậy của toàn bộ pipeline.

