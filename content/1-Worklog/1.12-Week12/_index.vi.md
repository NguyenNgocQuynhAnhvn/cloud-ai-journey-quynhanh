---
title: "Tuần 12"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---


**Mục tiêu trong tuần**

- Hoàn thiện và tối ưu toàn bộ hệ thống Customer Behavior Analytics trên nền tảng AWS.
- Kiểm thử và đánh giá toàn bộ pipeline Data Lakehouse nhằm đảm bảo tính chính xác, hiệu năng và độ ổn định của hệ thống.
- Hoàn thiện Dashboard, tài liệu kỹ thuật và các minh chứng phục vụ báo cáo, trình diễn và nghiệm thu dự án.
- Tổng kết kết quả thực hiện, đánh giá những mục tiêu đã đạt được.
---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Kiểm thử toàn bộ pipeline xử lý dữ liệu từ nguồn dữ liệu qua các tầng Raw, Bronze, Silver và Gold. Kiểm tra tính chính xác và nhất quán của dữ liệu sau mỗi bước xử lý. | 6/7 |
| Thứ Ba | Tối ưu hiệu suất truy vấn trên Amazon Athena đối với dữ liệu định dạng Apache Parquet. Kiểm tra khả năng truy vấn thông qua AWS Glue Data Catalog và đối chiếu kết quả với Dashboard. | 7/7 |
| Thứ Tư | Hoàn thiện Dashboard bằng Streamlit, tối ưu bố cục giao diện, các biểu đồ trực quan và kiểm tra khả năng truy cập, vận hành của ứng dụng trên Amazon EC2. | 8/7 |
| Thứ Năm (Lên văn phòng) | Chuẩn bị đầy đủ các hình ảnh minh chứng của hệ thống gồm Amazon S3, AWS Glue Jobs, AWS Glue Data Catalog, Amazon Athena, Dashboard và sơ đồ kiến trúc tổng thể. Hoàn thiện tài liệu kỹ thuật và nội dung demo dự án. | 9/7 |
| Thứ Sáu | Hoàn thiện báo cáo thực tập, Worklog và tài liệu hướng dẫn triển khai. Tổng kết kết quả thực hiện dự án, rà soát toàn bộ hệ thống và chuẩn bị cho buổi nghiệm thu. | 10/7 |

**Kết quả đạt được trong tuần là gì:**

- **Thứ Hai:**
  - **Kết quả đạt được:** Hoàn thành kiểm thử toàn bộ quy trình xử lý dữ liệu từ nguồn dữ liệu đến Gold Layer, xác nhận dữ liệu được xử lý đầy đủ, chính xác và nhất quán tại từng tầng của kiến trúc Medallion Data Lakehouse.
  - **Bài học:** Kiểm thử xuyên suốt toàn bộ pipeline giúp đảm bảo chất lượng dữ liệu và phát hiện sớm các sai lệch trước khi đưa vào khai thác thực tế.

- **Thứ Ba:**
  - **Kết quả đạt được:** Tối ưu thành công các truy vấn trên Amazon Athena và xác nhận dữ liệu truy vấn từ AWS Glue Data Catalog hoàn toàn trùng khớp với dữ liệu hiển thị trên Dashboard.
  - **Bài học:** Việc sử dụng Apache Parquet kết hợp với Athena giúp cải thiện đáng kể hiệu suất truy vấn, đồng thời giảm dung lượng dữ liệu cần quét và tối ưu chi phí vận hành.

- **Thứ Tư:**
  - **Kết quả đạt được:** Hoàn thiện Dashboard Streamlit với giao diện trực quan, các biểu đồ hiển thị đầy đủ chỉ số KPI và ứng dụng hoạt động ổn định trên Amazon EC2.
  - **Bài học:** Một Dashboard có giao diện rõ ràng và tốc độ phản hồi tốt giúp người dùng dễ dàng khai thác thông tin và nâng cao hiệu quả phân tích dữ liệu.

- **Thứ Năm (Lên văn phòng):**
  - **Kết quả đạt được:** Chuẩn bị đầy đủ hình ảnh minh chứng, tài liệu kỹ thuật, sơ đồ kiến trúc và nội dung demo, sẵn sàng phục vụ quá trình báo cáo và nghiệm thu dự án.
  - **Bài học:** Việc chuẩn bị đầy đủ tài liệu và minh chứng không chỉ giúp quá trình trình bày trở nên thuyết phục hơn mà còn tạo thuận lợi cho việc bàn giao và bảo trì hệ thống.

- **Thứ Sáu:**
  - **Kết quả đạt được:** Hoàn thành báo cáo thực tập, Worklog, tài liệu hướng dẫn triển khai và tổng kết toàn bộ dự án Customer Behavior Analytics trên nền tảng AWS.
  - **Bài học:** Giai đoạn tổng kết giúp đánh giá toàn diện kết quả đạt được, rút ra những kinh nghiệm thực tiễn về thiết kế, triển khai và vận hành một hệ thống Data Lakehouse Serverless trên AWS.