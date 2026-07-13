---
title: "Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

> **Thời gian:** 18/05/2026 - 24/05/2026 Ứng dụng AI/ML với Amazon SageMaker

---

### Mục tiêu trong tuần

- Nắm vững cách sử dụng Amazon SageMaker để thực hiện toàn bộ quy trình từ xây dựng, huấn luyện đến triển khai mô hình học máy.
- Học cách tích hợp các dịch vụ AI đã được huấn luyện sẵn của AWS vào ứng dụng mà không cần kiến thức chuyên sâu về mô hình thuật toán.
- Hiểu cách quản lý vòng đời của một dự án Machine Learning một cách chuyên nghiệp trên đám mây.

---

### Nội dung học tập

#### 1. Các thành phần cốt lõi của Machine Learning Essentials

- **Machine Learning with Amazon SageMaker:** Tìm hiểu tổng quan về các thành phần cốt lõi của SageMaker và lý do tại sao nó là nền tảng hàng đầu cho các nhà khoa học dữ liệu.
- **SageMaker Immersion Day:** một chuỗi các bước thực hành toàn diện (End-to-End ML Pipeline).
  + **Data Preparation (Chuẩn bị dữ liệu):** Học cách thu thập, làm sạch và biến đổi dữ liệu thô (thường lấy từ S3) thành các định dạng mà mô hình học máy có thể hiểu được.
  + **Build (Xây dựng mô hình):** Sử dụng các môi trường phát triển như Jupyter Notebook trong SageMaker để viết code, khám phá dữ liệu và chọn thuật toán phù hợp.
  + **Train (Huấn luyện):** Thực hành cấu hình các máy chủ mạnh mẽ (GPU/CPU) để chạy các tác vụ huấn luyện mô hình trên quy mô lớn chỉ với vài dòng lệnh hoặc thao tác trên bảng điều khiển.
  + **Tune (Tối ưu hóa):** Học cách sử dụng tính năng Hyperparameter Tuning để tự động tìm ra các tham số tốt nhất, giúp tối ưu hóa độ chính xác của mô hình.
  + **Deploy (Triển khai):** Thực hành đưa mô hình đã huấn luyện ra thực tế bằng cách tạo ra các Inference Endpoints, giúp các ứng dụng khác có thể gọi đến để dự báo dữ liệu theo thời gian thực.

#### 2. Tích hợp các dịch vụ AI thông minh (AI Services Integration)

- **AWS AI Services Integration:** Tìm hiểu cách gọi các API của AWS để tích hợp các tính năng thông minh như:
  + Nhận diện hình ảnh và video.
  + Phân tích cảm xúc văn bản và trích xuất thông tin.
  + Chuyển đổi ngôn ngữ và giọng nói.
  + Dự báo chuỗi thời gian mà không cần xây dựng mô hình từ đầu.

---

### Bài học rút ra

- **Hiểu được quy trình phát triển Machine Learning hoàn chỉnh:** Việc xây dựng một mô hình Machine Learning không chỉ dừng ở bước huấn luyện mà còn bao gồm các giai đoạn như chuẩn bị dữ liệu, huấn luyện, đánh giá, triển khai và theo dõi mô hình trong thực tế.
- **Hiểu được lợi ích của Amazon SageMaker trong phát triển AI/ML:** Amazon SageMaker giúp đơn giản hóa việc xây dựng, huấn luyện và triển khai các mô hình Machine Learning trên hạ tầng điện toán đám mây. Điều này cho phép xử lý các bài toán và tập dữ liệu lớn mà không phụ thuộc vào cấu hình của máy tính cá nhân.
- **Biết cách lựa chọn giải pháp AI phù hợp với từng bài toán:** Đối với những bài toán đặc thù có thể xây dựng mô hình riêng bằng Amazon SageMaker, trong khi các bài toán phổ biến có thể tận dụng các dịch vụ AI có sẵn của AWS để rút ngắn thời gian phát triển và tối ưu nguồn lực.
- **Hiểu được quy trình triển khai mô hình vào thực tế:** khi mô hình được huấn luyện và đánh giá, cần triển khai thành các API Endpoint để các ứng dụng có thể sử dụng. Điều này giúp hiểu rõ hơn về quy trình đưa mô hình Machine Learning từ môi trường phát triển vào vận hành trong thực tế.

---

*Nguồn tài liệu chính: [First Cloud Journey - AWS Study Group](https://cloudjourney.awsstudygroup.com/)*
