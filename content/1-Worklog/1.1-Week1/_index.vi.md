---
title: "Tuần 1"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

**Mục tiêu trong tuần**

- Thiết lập nền tảng an toàn: Làm quen với môi trường điện toán đám mây AWS, tạo tài khoản và thiết lập các lớp bảo mật, phân quyền cơ bản.
- Kiểm soát tài chính: Hiểu cách quản lý và giám sát chi phí để tránh phát sinh hóa đơn ngoài ý muốn khi thực hành các bài toán dữ liệu lớn.
- Nắm vững hạ tầng cơ bản: Hiểu về máy chủ ảo (EC2), mạng ảo (VPC) và lưu trữ đối tượng (S3). 
- Làm chủ công cụ thao tác: Biết cách sử dụng dòng lệnh (CLI) và môi trường lập trình trên Cloud (Cloud9) thay vì chỉ thao tác thủ công.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai (Lên văn phòng) | Tạo tài khoản AWS mới, hoàn tất thiết lập thanh toán và kích hoạt 100 USD credit khởi đầu. Khởi chạy và kiểm tra một EC2 instance dùng key pair tự tạo, sử dụng Claude 3 Haiku playground trong Bedrock, cấu hình cảnh báo chi phí trong AWS Budgets, tạo hàm Lambda cơ bản, và cung cấp một cơ sở dữ liệu PostgreSQL trên RDS. | 20/4 |
| Thứ Ba | Nghiên cứu và thực hành quản lý truy cập trên AWS IAM bằng cách tạo Users, Groups, Policies và phân quyền theo nguyên tắc đặc quyền tối thiểu (Least Privilege). Tìm hiểu cơ chế IAM Roles và Instance Profile, đồng thời cấu hình để EC2 truy cập Amazon S3 an toàn mà không cần sử dụng Access Key | 21/4 |
| Thứ Tư (Lên văn phòng) | Thiết kế và triển khai hạ tầng mạng ảo với Amazon VPC, thực hành cấu hình các thành phần cốt lõi như Subnets, Internet Gateway và Route Tables để xây dựng môi trường mạng biệt lập. Tìm hiểu và cấu hình EC2 Auto Scaling để tự động điều chỉnh số lượng máy chủ dựa trên nhu cầu tính toán thực tế, đảm bảo tính sẵn sàng cao cho hệ thống xử lý dữ liệu. | 22/4 |
| Thứ Năm | Thực hành lưu trữ dữ liệu và triển khai website tĩnh trên Amazon S3, nắm vững cách quản lý Bucket, chính sách truy cập đối tượng và các lớp lưu trữ. Thiết lập môi trường lập trình tích hợp trên đám mây với AWS Cloud9, đồng thời sử dụng giao diện dòng lệnh AWS CLI để thực hiện các thao tác quản trị tài nguyên một cách tự động và chuyên nghiệp | 23/4 |
| Thứ Sáu | Triển khai giải pháp giám sát tài nguyên tập trung bằng Amazon CloudWatch, thực hành xây dựng Dashboards theo dõi hiệu năng hệ thống và thiết lập Alarms cảnh báo tự động qua email. Nghiên cứu các gói dịch vụ và quy trình gửi yêu cầu hỗ trợ kỹ thuật thông qua AWS Support, đồng thời tổng kết biến động chi phí thực tế trên AWS Budgets sau một tuần thực hành. | 24/4 |

**Kết quả đạt được trong tuần là gì:**
- **Thứ Hai (Lên văn phòng):**
  - Kết quả đạt được: Kích hoạt thành công tài khoản AWS với tổng cộng 200 USD credit khuyến mại. Toàn bộ năm tài nguyên thử nghiệm đã được khởi chạy và xóa bỏ an toàn.
  - Bài học: Làm quen trực quan với giao diện điều khiển AWS Console và xây dựng thói quen dọn dẹp tài nguyên thực hành ngay lập tức để tránh phát sinh chi phí.
- **Thứ Ba:**
  - Kết quả đạt được: Thiết lập được một môi trường mạng an toàn, cô lập để đặt các máy chủ xử lý dữ liệu. Hiểu cơ chế tự động duy trì hiệu năng hệ thống khi khối lượng công việc thay đổi.
  - Bài học: Mạng ảo (VPC) là lớp bảo vệ đầu tiên của dữ liệu trên Cloud, việc cấu hình sai Subnet hoặc Route Table có thể dẫn đến rò rỉ dữ liệu hoặc mất kết nối.
- **Thứ Tư (Lên văn phòng)**
  - Kết quả đạt được: Thiết lập được một môi trường mạng an toàn, cô lập để đặt các máy chủ xử lý dữ liệu. Hiểu cơ chế tự động duy trì hiệu năng hệ thống khi khối lượng công việc thay đổi.
  - Bài học: Mạng ảo (VPC) là lớp bảo vệ đầu tiên của dữ liệu trên Cloud, việc cấu hình sai Subnet hoặc Route Table có thể dẫn đến rò rỉ dữ liệu hoặc mất kết nối.
- **Thứ Năm**
  - Kết quả đạt được: Lưu trữ và quản lý tệp tin thành công trên S3, có môi trường IDE (Cloud9) sẵn sàng để viết code mà không phụ thuộc máy tính cá nhân. Biết các lệnh CLI cơ bản để liệt kê và quản lý tài nguyên.
  - Bài học: S3 không chỉ là ổ cứng mà là một kho lưu trữ thông minh có khả năng mở rộng vô hạn. CLI là công cụ bắt buộc phải tốt để tự động hóa các quy trình (pipeline) sau này.
  - **Thứ Sáu**
  - Kết quả đạt được: Có hệ thống cảnh báo tự động qua email về tình trạng sức khỏe của hạ tầng. Hoàn thành tổng thể nền tảng hạ tầng an toàn.
  - Bài học: Luôn phải có biểu đồ theo dõi để biết hệ thống đang hoạt động như thế nào trước khi nó gặp sự cố thật sự.
