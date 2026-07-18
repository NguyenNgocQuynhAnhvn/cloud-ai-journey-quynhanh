---
title: "Tuần 10"
date: 2026-06-15
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---


**Mục tiêu trong tuần**

- Hoàn thiện Analytics & Visualization Layer cho hệ thống Customer Behavior Analytics trên nền tảng AWS.
- Xây dựng môi trường truy vấn dữ liệu bằng Amazon Athena và kết nối với AWS Glue Data Catalog.
- Phát triển Dashboard trực quan hóa dữ liệu bằng Streamlit và tích hợp với các dịch vụ AWS.
- Triển khai Dashboard lên Amazon EC2, kiểm tra toàn bộ hệ thống và đảm bảo khả năng truy cập từ Internet.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Thiết lập và cấu hình Amazon Athena kết nối với AWS Glue Data Catalog. Kiểm tra dữ liệu tại Gold Layer bằng các câu lệnh SQL và đánh giá hiệu suất truy vấn trên dữ liệu định dạng Apache Parquet. | 22/6 |
| Thứ Ba | Xây dựng Dashboard bằng Streamlit, thiết kế giao diện hiển thị các chỉ số KPI và biểu đồ phân tích. Tích hợp AWS Wrangler để truy vấn dữ liệu trực tiếp từ Amazon Athena. | 23/6 |
| Thứ Tư | Hoàn thiện các chức năng của Dashboard, xây dựng các biểu đồ phân tích về doanh thu, đơn hàng, khách hàng, quốc gia, thiết bị, phương thức thanh toán và nguồn truy cập. | 24/6 |
| Thứ Năm | Khởi tạo và cấu hình Amazon EC2, thiết lập VPC, Public Subnet, Internet Gateway, Route Table và Security Group. Cài đặt môi trường Python, AWS CLI và triển khai ứng dụng Streamlit lên EC2. | 25/6 |
| Thứ Sáu | Kiểm thử toàn bộ luồng dữ liệu từ Gold Layer → Amazon Athena → Streamlit Dashboard, xác nhận tính chính xác của dữ liệu, đánh giá hiệu suất và hoàn thiện tài liệu triển khai hệ thống. | 26/6 |

**Kết quả đạt được trong tuần là gì:**

- **Thứ Hai:**
  - **Kết quả đạt được:** Hoàn thành cấu hình Amazon Athena và kết nối thành công với AWS Glue Data Catalog. Dữ liệu tại Gold Layer được truy vấn chính xác thông qua các câu lệnh SQL.
  - **Bài học:** Athena cho phép truy vấn trực tiếp dữ liệu trên Amazon S3 mà không cần xây dựng hệ quản trị cơ sở dữ liệu riêng, giúp giảm chi phí và đơn giản hóa kiến trúc phân tích.

- **Thứ Ba:**
  - **Kết quả đạt được:** Xây dựng thành công giao diện Dashboard bằng Streamlit và tích hợp AWS Wrangler để truy vấn dữ liệu từ Amazon Athena.
  - **Bài học:** AWS Wrangler giúp đơn giản hóa việc kết nối giữa các dịch vụ AWS và Python, hỗ trợ truy xuất dữ liệu nhanh chóng để phục vụ trực quan hóa.

- **Thứ Tư:**
  - **Kết quả đạt được:** Hoàn thiện Dashboard với đầy đủ các chỉ số KPI và biểu đồ phân tích về doanh thu, đơn hàng, khách hàng, quốc gia, thiết bị, phương thức thanh toán và nguồn truy cập.
  - **Bài học:** Thiết kế Dashboard trực quan giúp người dùng dễ dàng theo dõi hiệu quả kinh doanh và đưa ra các quyết định dựa trên dữ liệu.

- **Thứ Năm:**
  - **Kết quả đạt được:** Triển khai thành công ứng dụng Streamlit lên Amazon EC2, cấu hình môi trường Python, AWS CLI và cho phép truy cập Dashboard thông qua địa chỉ Public IP.
  - **Bài học:** Việc triển khai trên EC2 giúp ứng dụng có thể truy cập từ Internet, đồng thời tạo môi trường linh hoạt để kiểm thử và vận hành hệ thống thực tế.

- **Thứ Sáu:**
  - **Kết quả đạt được:** Kiểm thử thành công toàn bộ luồng dữ liệu từ Gold Layer đến Dashboard, xác nhận dữ liệu hiển thị chính xác và hệ thống hoạt động ổn định.
  - **Bài học:** Kiểm thử toàn bộ Analytics & Visualization Layer giúp đảm bảo tính nhất quán giữa dữ liệu lưu trữ, dữ liệu truy vấn và dữ liệu trực quan hóa, tạo nền tảng cho việc đánh giá tổng thể hệ thống.
