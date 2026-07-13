---
title: "Tuần 1"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

> **Thời gian:** 20/04/2026 - 26/04/2026 Nền tảng Cloud và thiết lập môi trường an toàn

---

### Mục tiêu trong tuần

- Thiết lập nền tảng an toàn: Làm quen với môi trường điện toán đám mây AWS, tạo tài khoản và thiết lập các lớp bảo mật, phân quyền cơ bản.
- Kiểm soát tài chính: Hiểu cách quản lý và giám sát chi phí để tránh phát sinh hóa đơn ngoài ý muốn khi thực hành các bài toán dữ liệu lớn.
- Nắm vững hạ tầng cơ bản: Hiểu về máy chủ ảo (EC2), mạng ảo (VPC) và lưu trữ đối tượng (S3). 
- Làm chủ công cụ thao tác: Biết cách sử dụng dòng lệnh (CLI) và môi trường lập trình trên Cloud (Cloud9) thay vì chỉ thao tác thủ công.

---

### Nội dung học tập

#### 1. Quản trị tài khoản và chi phí

- **Creating Your First AWS Account**: Đăng ký tài khoản AWS, thiết lập thông tin thanh toán và các bước bảo mật cơ bản ban đầu.
- **Managing Costs with AWS Budgets**: Thực hành tạo một ngân sách (Budget). Học cách thiết lập các ngưỡng cảnh báo (ví dụ: khi chi phí đạt 5 hoặc 10) để nhận email thông báo, giúp kiểm soát chi tiêu khi làm việc với các tập dữ liệu lớn.
- **Getting Help with AWS Support**: Tìm hiểu cách mở "Support Ticket" để nhận sự trợ giúp từ đội ngũ kỹ thuật của AWS khi hệ thống gặp lỗi hoặc cần giải đáp về dịch vụ.

#### 2. Bảo mật và quản lý truy cập (IAM)

- **Access Management with IAM**: Thực hành tạo User (người dùng), Group (nhóm) và gán các Policy (chính sách quyền hạn). Học cách phân quyền "chỉ đọc" hoặc "toàn quyền" cho các tài nguyên.
- **Instance Profiling with IAM Roles for EC2**: Đây là bài học nâng cao về bảo mật. Thay vì lưu Access Key (khóa truy cập) nguy hiểm bên trong máy chủ, tạo một IAM Role và gắn nó vào máy chủ EC2 để máy chủ đó có quyền tự động truy cập an toàn vào các dịch vụ khác như S3.

#### 3. Hạ tầng mạng và máy chủ (VPC & EC2)

- **Networking Essentials with Amazon VPC**: Học cách thiết lập một mạng ảo riêng tư, bao gồm Subnet (mạng con), Route Tables (bảng định tuyến) và Internet Gateway để cho phép hoặc chặn truy cập từ internet vào máy chủ chứa dữ liệu.
- **Compute Essentials with Amazon EC2**: Thực hành khởi tạo một máy chủ ảo (Instance). Học cách chọn loại máy chủ (Instance Type), hệ điều hành (AMI) và thiết lập Key Pair để đăng nhập từ xa.
- **Scaling Applications with EC2 Auto Scaling**: Tìm hiểu cơ chế tự động tăng hoặc giảm số lượng máy chủ dựa trên lưu lượng truy cập hoặc khối lượng tính toán, đảm bảo hệ thống luôn ổn định khi xử lý dữ liệu nặng.

#### 4. Lưu trữ và công cụ phát triển

- **Static Website Hosting with Amazon S3**: Thông qua việc hướng dẫn lưu trữ website, nắm vững cách tạo Bucket, upload file và quản lý quyền truy cập dữ liệu trên S3.
- **Cloud Development with AWS Cloud9**: Thiết lập một môi trường lập trình tích hợp (IDE) ngay trên trình duyệt. Để có thể viết code Python, chạy kịch bản phân tích dữ liệu mà không cần cài đặt gì vào máy tính cá nhân.
- **Command Line Operations with AWS CLI**: Thực hành cài đặt và sử dụng dòng lệnh để điều khiển các dịch vụ AWS.

#### 5. Giám sát hệ thống

- **Monitoring with Amazon CloudWatch**: Học cách xem các biểu đồ về mức độ sử dụng CPU, lưu lượng mạng và thiết lập các báo động (Alarms) khi máy chủ hoạt động quá tải trong quá trình huấn luyện mô hình.

---

### Bài học rút ra

- **Hiểu được tầm quan trọng của việc phân quyền tài khoản**: Không nên sử dụng tài khoản Root trong các thao tác hằng ngày mà nên sử dụng IAM User với quyền được cấp phù hợp. Điều này giúp nâng cao tính bảo mật và hạn chế các rủi ro khi quản lý hệ thống.
- **Tầm quan trọng của việc quản lý chi phí**: Việc thiết lập AWS Budgets để theo dõi mức chi tiêu sẽ chủ động quản lý chi phí khi sử dụng các dịch vụ điện toán đám mây và tránh phát sinh những khoản phí ngoài mong muốn.
- **Tính linh hoạt của Cloud**: Nhận ra rằng thay vì nâng cấp máy tính cá nhân, có thể dễ dàng khởi tạo một máy chủ EC2 mạnh mẽ chỉ trong vài phút để xử lý các tập dữ liệu khổng lồ, sau đó tắt đi để tiết kiệm chi phí.
- **Vai trò của lưu trữ dữ liệu trên Amazon S3**: Amazon S3 không chỉ là nơi lưu trữ dữ liệu mà còn có độ bền cao, khả năng mở rộng tốt và dễ dàng tích hợp với nhiều dịch vụ AWS khác. Điều này giúp việc lưu trữ, quản lý và khai thác dữ liệu trở nên thuận tiện và hiệu quả hơn so với lưu trữ trên ổ cứng thông thường.

---

*Nguồn tài liệu chính: [First Cloud Journey - AWS Study Group](https://cloudjourney.awsstudygroup.com/)*
