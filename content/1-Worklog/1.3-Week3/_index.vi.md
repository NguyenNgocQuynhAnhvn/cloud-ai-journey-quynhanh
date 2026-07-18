---
title: "Tuần 3"
date: 2026-05-03
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---


**Mục tiêu trong tuần**

- Hiểu và xây dựng Data Lake: Nắm vững khái niệm và cách triển khai một hồ dữ liệu (Data Lake) trên nền tảng Amazon S3.
- Quy trình ETL: Học cách trích xuất, biến đổi và nạp dữ liệu (Extract, Transform, Load) bằng các công cụ chuyên dụng của AWS
- Tự động hóa xử lý dữ liệu: Sử dụng các dịch vụ không máy chủ (Serverless) để xây dựng các đường ống dữ liệu (data pipelines) tự động.
- Tối ưu hóa quản lý dữ liệu: Biết cách tổ chức dữ liệu một cách khoa học để tối ưu cho việc truy vấn và phân tích ở các tuần sau.


---

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Nghiên cứu các khái niệm cốt lõi về kiến trúc hồ dữ liệu, tập trung vào vai trò trung tâm của Amazon S3 trong việc lưu trữ dữ liệu thô và dữ liệu đã qua xử lý. Thực hành thiết lập cấu trúc phân tầng dữ liệu và tìm hiểu các nguyên tắc quản lý vòng đời (Lifecycle Policy) để tối ưu hóa chi phí lưu trữ cho các tập dữ liệu lớn  | 4/5 |
| Thứ Ba (Lên văn phòng) | Thực hành quy trình đưa dữ liệu thực tế vào môi trường Cloud. Nghiên cứu cách tổ chức dữ liệu theo phương pháp Partitioning (phân vùng) để tối ưu hóa tốc độ truy vấn và quản lý quyền truy cập chi tiết cho từng vùng dữ liệu nghiên cứu. | 5/5 |
| Thứ Tư (Lên văn phòng) | Nghiên cứu  toàn bộ vòng đời của dữ liệu từ khâu thu thập (Ingestion), lưu trữ đến biến đổi (Transformation). Nghiên cứu cách phối hợp giữa các dịch vụ để tạo ra một đường ống dữ liệu (Data Pipeline) sạch, phục vụ cho các mô hình Machine Learning. | 6/5 |
| Thứ Năm | Nghiên cứu và thực hành xây dựng danh mục dữ liệu tự động bằng AWS Glue Crawlers và thực hiện biến đổi định dạng dữ liệu để tối ưu hiệu năng. Sử dụng Amazon Athena để thực hiện truy vấn SQL trực tiếp trên dữ liệu lưu trữ tại S3 (Data Lake) mà không cần quản lý hạ tầng máy chủ. | 7/5 |
| Thứ Sáu | Nghiên cứu và thực hành tự động hóa xử lý dữ liệu bằng AWS Lambda, đồng thời sử dụng AWS Step Functions để điều phối các workflow nhiều bước, đảm bảo tính logic và khả năng tự phục hồi khi xảy ra lỗi. | 8/5 |

**Kết quả đạt được trong tuần là gì:**
- **Thứ Hai:**
  - Kết quả đạt được: Nắm vững kiến trúc phân tầng trong Data Lake; thiết lập thành công các chính sách lưu trữ tự động trên S3.
  - Bài học: Data Lake không chỉ là nơi chứa file mà là nền tảng quản trị dữ liệu có tổ chức, giúp dữ liệu luôn sẵn sàng cho các mục đích phân tích khác nhau mà không cần cấu trúc hóa ngay từ đầu.
- **Thứ Ba (Lên văn phòng):**
  - Kết quả đạt được: Xây dựng thành công một Data Lake cấu hình được các Buckets an toàn và có hiệu suất truy xuất cao.
  - Bài học: Việc phân vùng dữ liệu (ví dụ theo năm/tháng/ngày) là yếu tố quan trọng để giảm chi phí truy vấn và tăng tốc độ xử lý khi làm việc với Big Data.
- **Thứ Tư (Lên văn phòng):**
  - Kết quả đạt được: Hoàn thành quy trình ETL (Extract, Transform, Load) cơ bản; hiểu rõ cách dòng chảy dữ liệu vận hành qua các dịch vụ khác nhau trên AWS.
  - Bài học: Dữ liệu "sạch" và được cấu trúc tốt là nền tảng để có một mô hình AI chính xác.
- **Thứ Năm:**
  - Kết quả đạt được: Tự động hóa được việc nhận diện lược đồ dữ liệu (schema); thực hiện thành công các truy vấn SQL phức tạp trên dữ liệu thô với tốc độ nhanh và chi phí thấp.
  - Bài học: Các dịch vụ Serverless như AWS Glue và Amazon Athena, giúp tập trung vào phân tích dữ liệu mà không cần quản lý hạ tầng.
- **Thứ Sáu:**
  - Kết quả đạt được: Xây dựng thành công một hệ thống xử lý dữ liệu tự động hoàn toàn (Event-driven), thiết lập được quy trình điều phối có khả năng giám sát trạng thái từng bước.
  - Bài học: Tự động hóa và điều phối luồng công việc giúp hệ thống dữ liệu vận hành ổn định 24/7, giảm thiểu sai sót do thao tác thủ công và tăng tính chuyên nghiệp cho dự án.