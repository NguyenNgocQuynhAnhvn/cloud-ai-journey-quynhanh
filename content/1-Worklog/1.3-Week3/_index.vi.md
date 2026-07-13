---
title: "Tuần 3"
date: 2026-05-03
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

> **Thời gian:** 04/05/2026 - 10/05/2026 Xây dựng Data Lake và Data Engineering

---

### Mục tiêu trong tuần

- Hiểu và xây dựng Data Lake: Nắm vững khái niệm và cách triển khai một hồ dữ liệu (Data Lake) trên nền tảng Amazon S3.
- Quy trình ETL: Học cách trích xuất, biến đổi và nạp dữ liệu (Extract, Transform, Load) bằng các công cụ chuyên dụng của AWS
- Tự động hóa xử lý dữ liệu: Sử dụng các dịch vụ không máy chủ (Serverless) để xây dựng các đường ống dữ liệu (data pipelines) tự động.
- Tối ưu hóa quản lý dữ liệu: Biết cách tổ chức dữ liệu một cách khoa học để tối ưu cho việc truy vấn và phân tích ở các tuần sau.


---

### Nội dung học tập

#### 1. Nền tảng và xây dựng hồ dữ liệu (Data Lake)

- **Data Lake Fundamentals on AWS:** Học các khái niệm cơ bản về kiến trúc hồ dữ liệu, cách phân tầng dữ liệu (thô, đã xử lý, sẵn sàng phân tích) và tại sao Amazon S3 là lựa chọn tối ưu cho Data Lake.
- **Building a Data Lake with Your Own Data:** Thực hành đưa dữ liệu thực tế lên S3, thiết lập cấu trúc thư mục (prefix) và quản lý vòng đời dữ liệu.
 
#### 2. Kỹ thuật dữ liệu chuyên sâu (Data Engineering)

- **Data Engineering Immersion Day:** Thực hành toàn diện bao gồm các giai đoạn: Thu thập (Ingestion), lưu trữ (Storage), xử lý (Processing) và phân tích (Analytics). Hiểu cách các dịch vụ phối hợp với nhau trong một dự án thực tế.
- **Cost Data Analysis with AWS Glue and Amazon Athena:** Sử dụng AWS Glue Crawlers để tự động quét dữ liệu trên S3 và tạo bảng trong AWS Glue Data Catalog. Học cách sử dụng AWS Glue ETL jobs để làm sạch, định dạng lại dữ liệu (ví dụ: chuyển từ CSV sang Parquet để tối ưu tốc độ truy vấn).

#### 3. Phân tích dữ liệu không máy chủ (Serverless Analytics)

- **Serverless Analytics with Amazon Athena:** Thực hành viết các câu lệnh SQL chuẩn để truy vấn trực tiếp dữ liệu nằm trên Amazon S3. Học cách tối ưu hóa hiệu suất truy vấn và giảm chi phí thông qua việc phân vùng dữ liệu (partitioning).

#### 4. Tự động hóa và điều phối quy trình (Automation & Orchestration)

- **Serverless Automation with AWS Lambda:**  Học cách viết các hàm nhỏ để tự động kích hoạt quá trình xử lý ngay khi có tệp dữ liệu mới được tải lên Data Lake.
- **Workflow Orchestration with AWS Step Functions:** Thực hành thiết kế các quy trình xử lý dữ liệu gồm nhiều bước (ví dụ: Bước 1 - Kiểm tra dữ liệu -> Bước 2 - Chạy Glue Job -> Bước 3 - Gửi thông báo) theo một trình tự logic và có khả năng xử lý lỗi tự động.

#### 5. Tổ chức và quản lý tài nguyên

- **Resource Organization with Tags and Resource Groups**: Học cách gắn nhãn (tags) cho các tài nguyên dữ liệu để dễ dàng quản lý theo từng dự án hoặc giai đoạn nghiên cứu.

---

### Bài học rút ra

- **Hiểu được vai trò của Data Lake trong lưu trữ dữ liệu:** Amazon S3 không chỉ là nơi lưu trữ dữ liệu mà còn đóng vai trò là trung tâm của hệ thống phân tích dữ liệu. S3 cho phép lưu trữ cả dữ liệu thô và dữ liệu đã được xử lý với khả năng mở rộng cao, chi phí hợp lý và thuận tiện cho việc khai thác dữ liệu sau này.
- **Hiểu được lợi ích của mô hình Serverless:** AWS Glue và Amazon Athena có thể xử lý và truy vấn dữ liệu mà không cần quản lý máy chủ.
- **Nhận thức được tầm quan trọng của quá trình ETL và chuẩn hóa dữ liệu:** Việc làm sạch, chuyển đổi và chuẩn hóa dữ liệu là bước rất quan trọng trước khi phân tích hoặc xây dựng mô hình Machine Learning. Dữ liệu được chuẩn bị tốt sẽ góp phần nâng cao độ chính xác và hiệu quả của các mô hình.
- **Hiểu được vai trò của tự động hóa trong xử lý dữ liệu:** AWS Lambda và AWS Step Functions tự động hóa giúp giảm các thao tác thủ công, xây dựng quy trình xử lý dữ liệu nhất quán và giúp hệ thống tự động thực hiện các tác vụ khi có dữ liệu mới được đưa vào.
---

*Nguồn tài liệu chính: [First Cloud Journey - AWS Study Group](https://cloudjourney.awsstudygroup.com/)*
