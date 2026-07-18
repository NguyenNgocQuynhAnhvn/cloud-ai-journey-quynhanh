---
title: "Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


**Mục tiêu trong tuần**

- Nắm vững cách sử dụng Amazon SageMaker để thực hiện toàn bộ quy trình từ xây dựng, huấn luyện đến triển khai mô hình học máy.
- Học cách tích hợp các dịch vụ AI đã được huấn luyện sẵn của AWS vào ứng dụng mà không cần kiến thức chuyên sâu về mô hình thuật toán.
- Hiểu cách quản lý vòng đời của một dự án Machine Learning một cách chuyên nghiệp trên đám mây.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Nghiên cứu Amazon SageMaker và cách quản lý vòng đời Machine Learning, đồng thời thiết lập môi trường phát triển với SageMaker Studio hoặc Notebook Instances để triển khai các dự án phân tích dữ liệu. | 18/5 |
| Thứ Ba | Thực hành các bước Data Preparation và Build trong SageMaker Immersion Day, bao gồm thu thập dữ liệu từ Amazon S3, tiền xử lý, Feature Engineering và xây dựng mô hình trên Jupyter Notebook. | 19/5 |
| Thứ Tư | Thực hành huấn luyện mô hình với Amazon SageMaker bằng Training Jobs và sử dụng Hyperparameter Tuning để tự động tối ưu tham số, nâng cao hiệu quả mô hình. | 20/5 |
| Thứ Năm | Thực hành triển khai mô hình trên Amazon SageMaker dưới dạng Inference Endpoint, kiểm thử dự báo qua API thời gian thực và giám sát hiệu suất mô hình sau khi triển khai. | 21/5 |
| Thứ Sáu | Nghiên cứu và thực hành tích hợp các dịch vụ AI của AWS, sử dụng API cho các tác vụ như nhận diện hình ảnh, phân tích cảm xúc và dịch thuật để bổ sung tính năng AI cho ứng dụng. | 22/5 |

**Kết quả đạt được trong tuần là gì:**
- **Thứ Hai:**
  - Kết quả đạt được: Hiểu rõ các thành phần cấu thành nên hệ sinh thái ML trên AWS, khởi tạo thành công môi trường lập trình Notebook sẵn sàng cho việc huấn luyện mô hình.
  - Bài học: việc sử dụng nền tảng Managed Service giúp giảm bớt gánh nặng quản trị hạ tầng tính toán (GPU/CPU).
- **Thứ Ba:**
  - Kết quả đạt được: Xây dựng được tập dữ liệu sạch sẵn sàng cho việc huấn luyện, làm chủ giao diện SageMaker Studio để quản lý mã nguồn và dữ liệu hiệu quả.
  - Bài học: Giai đoạn chuẩn bị dữ liệu luôn chiếm phần lớn thời gian nhưng đóng vai trò quan trọng trong việc quyết định chất lượng và độ chính xác của mô hình học máy sau này.
- **Thứ Tư:**
  - Kết quả đạt được: Huấn luyện thành công các mô hình học máy, tìm ra bộ tham số tối ưu thông qua các thử nghiệm tự động mà không cần can thiệp thủ công nhiều lần.
  - Bài học: Việc điều chỉnh tham số giúp tiết kiệm đáng kể thời gian và giúp khám phá ra các cấu hình mô hình mà các phương pháp thử nghiệm thủ công có thể bỏ sót.
- **Thứ Năm:**
  - Kết quả đạt được: Triển khai thành công mô hình học máy dưới dạng một web service, có khả năng lấy kết quả dự báo từ ứng dụng thực tế.
  - Bài học: Quy trình đưa mô hình từ môi trường nghiên cứu ra thực tế (Production) phải có kỹ năng đóng gói mô hình và quản lý điểm cuối (Endpoint) để đảm bảo hệ thống luôn sẵn sàng phục vụ.
- **Thứ Sáu:**
  - Kết quả đạt được: Hiểu và vận dụng các dịch vụ AI của AWS, đồng thời phân biệt kịch bản sử dụng giữa Amazon SageMaker và các dịch vụ AI dựng sẵn để lựa chọn giải pháp phù hợp.
  - Bài học:  Việc tận dụng các dịch vụ AI đã được tối ưu hóa giúp tăng tốc độ phát triển và giảm thiểu chi phí bảo trì so với việc tự xây dựng mô hình từ đầu.