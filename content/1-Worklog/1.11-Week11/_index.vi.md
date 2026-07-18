---
title: "Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---


**Mục tiêu trong tuần**

- Hoàn thiện việc tích hợp toàn bộ các thành phần của hệ thống Customer Behavior Analytics trên nền tảng AWS.
- Kiểm thử quy trình xử lý dữ liệu xuyên suốt từ nguồn dữ liệu đến Dashboard theo mô hình Data Lakehouse.
- Đánh giá tính chính xác, hiệu năng và độ ổn định của hệ thống trong các kịch bản Batch Processing và Streaming Processing.
- Hoàn thiện kiến trúc End-to-End và chuẩn bị tài liệu phục vụ báo cáo, nghiệm thu và trình bày kết quả dự án.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Tích hợp toàn bộ các thành phần của hệ thống gồm Ingestion Layer, Data Processing Layer, Query Layer và Dashboard. Kiểm tra khả năng kết nối giữa các dịch vụ AWS trong toàn bộ pipeline. | 29/6 |
| Thứ Ba | Kiểm thử toàn bộ quy trình xử lý dữ liệu từ Raw → Bronze → Silver → Gold, thực hiện nhiều lần chạy thử các pipeline Batch Processing và Streaming Processing để đánh giá tính ổn định của hệ thống. | 30/6 |
| Thứ Tư | Kiểm tra dữ liệu tại từng tầng của kiến trúc Medallion, đối chiếu dữ liệu giữa Amazon S3, Amazon Athena và Dashboard nhằm xác nhận tính chính xác và nhất quán của dữ liệu. | 1/7 |
| Thứ Năm | Kiểm thử khả năng cập nhật dữ liệu khi phát sinh dữ liệu mới, xác minh Dashboard tự động phản ánh các thay đổi sau quá trình xử lý. Khắc phục các lỗi phát sinh và tối ưu quy trình xử lý dữ liệu. | 2/7 |
| Thứ Sáu | Hoàn thiện sơ đồ kiến trúc tổng thể, cập nhật tài liệu kỹ thuật, quy trình triển khai và chuẩn bị nội dung phục vụ báo cáo, nghiệm thu và thuyết trình dự án. | 3/7 |

**Kết quả đạt được trong tuần là gì:**

- **Thứ Hai:**
  - **Kết quả đạt được:** Hoàn thành việc tích hợp toàn bộ các thành phần của hệ thống Customer Behavior Analytics và xác nhận các dịch vụ AWS phối hợp hoạt động đúng theo thiết kế.
  - **Bài học:** Việc tích hợp các thành phần theo từng lớp giúp dễ dàng kiểm soát luồng dữ liệu, đồng thời thuận tiện cho việc mở rộng và bảo trì hệ thống sau này.

- **Thứ Ba:**
  - **Kết quả đạt được:** Kiểm thử thành công các pipeline Batch Processing và Streaming Processing qua nhiều lần chạy, xác nhận hệ thống vận hành ổn định và xử lý dữ liệu liên tục.
  - **Bài học:** Kiểm thử lặp lại trong nhiều kịch bản khác nhau giúp đánh giá độ ổn định của hệ thống và phát hiện sớm các lỗi tiềm ẩn trước khi đưa vào sử dụng.

- **Thứ Tư:**
  - **Kết quả đạt được:** Xác nhận dữ liệu được xử lý chính xác và nhất quán tại các tầng Raw, Bronze, Silver và Gold; kết quả truy vấn trên Amazon Athena trùng khớp với dữ liệu hiển thị trên Dashboard.
  - **Bài học:** Việc đối chiếu dữ liệu giữa các tầng xử lý và lớp trực quan hóa giúp đảm bảo tính toàn vẹn và độ tin cậy của toàn bộ hệ thống phân tích dữ liệu.

- **Thứ Năm:**
  - **Kết quả đạt được:** Kiểm tra thành công khả năng cập nhật dữ liệu theo thời gian thực và theo lô, Dashboard phản ánh chính xác dữ liệu mới sau khi hoàn thành quá trình xử lý. Đồng thời khắc phục các lỗi phát sinh trong quá trình kiểm thử.
  - **Bài học:** Kiểm thử End-to-End không chỉ xác nhận tính đúng đắn của dữ liệu mà còn giúp đánh giá khả năng phối hợp giữa các thành phần trong toàn bộ pipeline.

- **Thứ Sáu:**
  - **Kết quả đạt được:** Hoàn thiện tài liệu kỹ thuật, sơ đồ kiến trúc tổng thể và quy trình triển khai hệ thống, sẵn sàng phục vụ báo cáo, nghiệm thu và trình bày dự án.
  - **Bài học:** Tài liệu đầy đủ và kiến trúc được chuẩn hóa giúp quá trình bàn giao, bảo trì và phát triển hệ thống trong tương lai trở nên dễ dàng và hiệu quả hơn.