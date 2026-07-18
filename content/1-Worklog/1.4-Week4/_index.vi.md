---
title: "Tuần 4"
date: 2026-05-10
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---


**Mục tiêu trong tuần**

- Học cách sử dụng Amazon QuickSight để xây dựng các Dashboard chuyên nghiệp, hỗ trợ ra quyết định.
- Hiểu rõ các dịch vụ phân tích khác nhau trên AWS và cách chọn dịch vụ phù hợp cho từng bài toán cụ thể.
-  Ứng dụng kỹ năng phân tích vào chính việc quản lý tài nguyên Cloud thông qua phân tích chi phí và hiệu năng.
- Kết hợp các kỹ năng từ tuần trước để chuẩn bị dữ liệu đầu vào tốt nhất cho việc trực quan hóa.

---

**Các công việc cần triển khai trong tuần này:**

| Thứ | Công việc | Ngày |
|---|---|---|
| Thứ Hai | Nghiên cứu các dịch vụ phân tích dữ liệu trên AWS và so sánh Amazon Athena, Amazon EMR, Amazon Redshift để hiểu đặc điểm, ưu điểm và lựa chọn dịch vụ phù hợp cho từng nhu cầu xử lý dữ liệu. | 11/5 |
| Thứ Ba | Thực hành xây dựng báo cáo với Amazon QuickSight bằng cách kết nối dữ liệu từ Amazon S3 và Amazon Athena, đồng thời tạo Datasets, thiết kế biểu đồ trực quan và xuất bản Dashboard phục vụ phân tích dữ liệu. | 12/5 |
| Thứ Tư | Thực hành phân tích chi phí AWS thông qua Cost and Usage Report, sử dụng các công cụ trực quan hóa để theo dõi mức sử dụng tài nguyên và tối ưu hóa ngân sách dự án. | 13/5 |
| Thứ Năm | Thực hành giám sát hệ thống với Amazon CloudWatch và Grafana, tích hợp các metrics vào Dashboard để theo dõi trạng thái của đường ống dữ liệu và máy chủ theo thời gian thực. | 14/5 |
| Thứ Sáu | Nghiên cứu quản lý chi phí và tài nguyên trên AWS, sử dụng Tags và Resource Groups để tổ chức tài nguyên, đồng thời phân tích mức sử dụng nhằm tối ưu cấu hình dịch vụ theo nhu cầu thực tế. | 15/5 |

**Kết quả đạt được trong tuần là gì:**
- **Thứ Hai:**
  - Kết quả đạt được: Phân biệt được các kịch bản sử dụng của từng dịch vụ phân tích, thiết lập được sơ đồ luồng dữ liệu từ Data Lake đến các công cụ phân tích.
  - Bài học: Việc chọn đúng công cụ phân tích không chỉ ảnh hưởng đến tốc độ xử lý mà còn quyết định sự tối ưu về chi phí cho các tập dữ liệu có quy mô khác nhau.
- **Thứ Ba:**
  - Kết quả đạt được: Xây dựng thành công một Dashboard phân tích dữ liệu hoàn chỉnh, có khả năng lọc và tương tác trực quan, nắm vững cách quản lý quyền truy cập báo cáo.
  - Bài học: QuickSight giúp chuyển đổi các kết quả truy vấn SQL khô khan thành thông tin có giá trị thực tiễn.
- **Thứ Tư:**
  - Kết quả đạt được: Tạo được các biểu đồ theo dõi biến động chi phí theo thời gian và theo từng dịch vụ.
  - Bài học: Việc giám sát chi phí thường xuyên giúp đảm bảo dự án không bị gián đoạn do vượt ngân sách.
- **Thứ Năm:**
  - Kết quả đạt được: Thiết lập thành công hệ thống giám sát tập trung; xây dựng được các biểu đồ theo dõi hiệu năng (CPU, RAM, Latency) của các dịch vụ phân tích.
  - Bài học: Giám sát chuyên sâu giúp phát hiện sớm các điểm nghẽn (bottleneck) trong quá trình xử lý dữ liệu trước khi chúng gây ra lỗi hệ thống.
- **Thứ Sáu:**
  - Kết quả đạt được: Áp dụng hệ thống nhãn (tagging) nhất quán cho toàn bộ hạ tầng phân tích; hoàn thành báo cáo đánh giá hiệu quả sử dụng tài nguyên của tuần.
  - Bài học: Quản lý tài nguyên bằng thẻ (tags) giúp phân tích chi phí chính xác cho từng dự án hoặc từng thành viên trong nhóm nghiên cứu.
