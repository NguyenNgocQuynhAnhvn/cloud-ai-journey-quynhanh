---
title: "Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

> **Thời gian:** 25/05/2026 - 31/05/2026 Tối ưu hóa, bảo mật và vận hành Hệ thống MLOps

---

### Mục tiêu trong tuần

- **Tự động hóa hạ tầng (IaC):** Học cách quản lý tài nguyên AWS bằng mã nguồn để có thể tái sử dụng và triển khai nhanh chóng các môi trường thí nghiệm.
- **Thiết lập quy trình CI/CD:** Xây dựng các đường ống triển khai tự động, giúp cập nhật mô hình hoặc mã nguồn xử lý dữ liệu một cách liên tục.
- **Thắt chặt bảo mật dữ liệu:** Áp dụng các phương thức mã hóa và quản lý quyền truy cập chuyên sâu để bảo vệ tài sản dữ liệu và mô hình.
- **Tối ưu hóa chi phí và hiệu năng:** Biết cách chọn lựa các gói chi phí tiết kiệm và tinh chỉnh tài nguyên để dự án hoạt động hiệu quả nhất về mặt kinh phí.

---

### Nội dung học tập

#### 1. Hạ tầng dưới dạng mã (Infrastructure as Code - IaC):

- **Infrastructure as Code with AWS CloudFormation:** Học cách sử dụng template để khởi tạo toàn bộ môi trường Data Science (S3, EC2, SageMaker) một cách tự động.
- **Cloud Development Kit (AWS CDK) Essentials:** Sử dụng các ngôn ngữ lập trình quen thuộc (như Python) để định nghĩa tài nguyên AWS, giúp việc quản lý hạ tầng trở nên gần gũi hơn.

#### 2. Triển khai liên tục (CI/CD) cho ML

- **CI/CD Pipeline with AWS CodePipeline:** Thực hành xây dựng quy trình tự động từ khâu đẩy code lên kho lưu trữ đến khi triển khai mô hình lên các môi trường thử nghiệm hoặc thực tế.
- **Automated Deployments with AWS CodePipeline:** Tìm hiểu sâu hơn về cách tự động hóa các bước kiểm thử và triển khai ứng dụng.

#### 3. Bảo mật dữ liệu nâng cao và quản lý chi phí chuyên sâu

- **Encryption with AWS Key Management Service (KMS):** Học cách mã hóa dữ liệu trong Data Lake (S3) và các cơ sở dữ liệu để đảm bảo an toàn tuyệt đối.
- **S3 Security Best Practices:** Nắm vững các quy tắc bảo mật tốt nhất hồ dữ liệu của.
- **Cost Savings with Savings Plans and Reserved Instances:** Tìm hiểu cách tiết kiệm lên đến 72% chi phí cho các máy chủ EC2 hoặc SageMaker Instances bằng các gói cam kết sử dụng lâu dài.
- **Right-Sizing with EC2 Resource Optimization:** Học cách điều chỉnh kích cỡ máy chủ sao cho phù hợp nhất với khối lượng tính toán, tránh lãng phí.

---

### Bài học rút ra

- **Hiểu được vai trò của MLOps trong triển khai Machine Learning:** Việc xây dựng một mô hình có độ chính xác cao chỉ là một phần của dự án. Để mô hình hoạt động ổn định trong thực tế, cần có quy trình quản lý, triển khai, cập nhật và giám sát mô hình một cách hiệu quả.
- **Hiểu được lợi ích của việc quản lý hạ tầng bằng mã nguồn:** hạ tầng có thể được định nghĩa bằng mã nguồn, giúp việc triển khai, sao chép và quản lý hệ thống trở nên nhanh chóng, nhất quán và hạn chế sai sót so với cấu hình thủ công.
- **Nâng cao nhận thức về bảo mật dữ liệu trên AWS:** Việc mã hóa dữ liệu và phân quyền truy cập phù hợp nhằm bảo vệ thông tin, đồng thời đảm bảo an toàn cho hệ thống và dữ liệu trong quá trình triển khai các ứng dụng AI/ML.
- **Hiểu được tầm quan trọng của việc tối ưu hiệu năng và chi phí:** Việc cân bằng giữa hiệu năng hệ thống và chi phí sử dụng tài nguyên giúp lựa chọn cấu hình phù hợp, sử dụng tài nguyên hiệu quả và duy trì khả năng vận hành lâu dài của dự án.

---

*Nguồn tài liệu chính: [First Cloud Journey - AWS Study Group](https://cloudjourney.awsstudygroup.com/)*
