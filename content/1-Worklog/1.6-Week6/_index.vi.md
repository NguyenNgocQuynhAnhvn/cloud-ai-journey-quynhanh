---
title: "Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---


**Mục tiêu trong tuần**

- **Tự động hóa hạ tầng (IaC):** Học cách quản lý tài nguyên AWS bằng mã nguồn để có thể tái sử dụng và triển khai nhanh chóng các môi trường thí nghiệm.
- **Thiết lập quy trình CI/CD:** Xây dựng các đường ống triển khai tự động, giúp cập nhật mô hình hoặc mã nguồn xử lý dữ liệu một cách liên tục.
- **Thắt chặt bảo mật dữ liệu:** Áp dụng các phương thức mã hóa và quản lý quyền truy cập chuyên sâu để bảo vệ tài sản dữ liệu và mô hình.
- **Tối ưu hóa chi phí và hiệu năng:** Biết cách chọn lựa các gói chi phí tiết kiệm và tinh chỉnh tài nguyên để dự án hoạt động hiệu quả nhất về mặt kinh phí.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Nghiên cứu và thực hành Infrastructure as Code (IaC) với AWS CloudFormation và AWS CDK, định nghĩa các tài nguyên như Amazon S3, Amazon EC2 và Amazon SageMaker để tự động hóa triển khai hạ tầng. | 25/5 |
| Thứ Ba | Thực hành quản trị hệ thống với AWS Systems Manager và Session Manager, đồng thời sử dụng Resource Groups và Resource Tags để tổ chức tài nguyên và quản lý quyền truy cập. | 26/5 |
| Thứ Tư | Thực hành bảo mật dữ liệu với AWS KMS và AWS Secrets Manager, đồng thời áp dụng các S3 Security Best Practices để bảo vệ Data Lake khỏi truy cập trái phép. | 27/5 |
| Thứ Năm | Thực hành xây dựng quy trình CI/CD với AWS CodePipeline và sử dụng AWS Step Functions để tự động hóa, điều phối quy trình huấn luyện và triển khai mô hình. | 28/5 |
| Thứ Sáu | Nghiên cứu Savings Plans và Reserved Instances, đồng thời thực hành tối ưu kích thước Amazon EC2 để giảm chi phí và sử dụng tài nguyên hiệu quả. | 29/5 |

**Kết quả đạt được trong tuần là gì:**
- **Thứ Hai:**
  - Kết quả đạt được: Khởi chạy thành công một hệ thống tài nguyên phức tạp chỉ bằng một bản thiết kế (template), nắm vững cách quản lý phiên bản cho hạ tầng.
  - Bài học: Việc sử dụng IaC giúp loại bỏ sai sót do thao tác thủ công và cho phép nhân bản môi trường làm việc chỉ trong vài phút thay vì phải cấu hình lại từ đầu.
- **Thứ Ba:**
  - Kết quả đạt được: Điều khiển được máy chủ từ xa qua trình duyệt, thiết lập được hệ thống phân loại tài nguyên thông minh theo từng dự án nghiên cứu.
  - Bài học: Quản trị hệ thống tốt giúp tăng tính bảo mật và giúp việc theo dõi các tài nguyên đang chạy trở nên dễ dàng hơn khi quy mô dự án ngày càng lớn.
- **Thứ Tư:**
  - Kết quả đạt được: Toàn bộ dữ liệu quan trọng và thông tin kết nối được mã hóa an toàn, thiết lập được cơ chế tự động xoay vòng (rotation) mật khẩu cho hệ thống. 
  - Bài học: Việc mã hóa và bảo mật dữ liệu nhằm bảo vệ mô hình học máy và thông tin khách hàng.
- **Thứ Năm:**
  - Kết quả đạt được: Thiết lập thành công quy trình MLOps cơ bản, mô hình tự động được cập nhật khi có thay đổi trong mã nguồn hoặc dữ liệu.
  - Bài học:  Tự động hóa quy trình triển khai giúp giảm thiểu thời gian chờ đợi và đảm bảo mô hình thực tế luôn là phiên bản mới nhất và tốt nhất.
- **Thứ Sáu:**
  - Kết quả đạt được: Hoàn thành báo cáo tối ưu hóa ngân sách.
  - Bài học: Một hệ thống Cloud tốt không chỉ hoạt động ổn định mà còn phải được tối ưu chi phí để sử dụng tài nguyên hiệu quả.