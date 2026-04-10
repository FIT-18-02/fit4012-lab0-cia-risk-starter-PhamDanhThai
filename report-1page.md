# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài labNhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
Phân biệt Confidentiality, Integrity, Availability.
Xác định threat, vulnerability, mitigation.
Thực hành workflow GitHub cơ bản để nhận và nộp bài.
### 2. Cách làm
Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
Phân tích từng sự cố theo bộ ba CIA.
Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
Hoàn thiện bài làm trong repo và commit/push lên GitHub.
### 3. Kết quả chính
**Assets:**
- Xác định được các assets quan trọng  
- Phân loại chính xác các sự cố theo CIA  
- Đề xuất các biện pháp giảm thiểu rủi ro phù hợp  

**CIA mapping:**

Sự cố A -> Availability
Sự cố B -> Integrity
Sự cố C -> Confidentiality
- 
**Phân tích sự cố B:**
  Threat: Người dùng trái phép hoặc người nội bộ sửa điểm không đúng quyền
  Vulnerability: Mật khẩu yếu, không có MFA, phân quyền chưa rõ ràng, không có log theo dõi
  Mitigation: Bật MFA, phân quyền rõ ràng, ghi log thay đổi điểm, yêu cầu phê duyệt khi chỉnh sửa

### 4. Kết luận ngắn

Qua bài lab này, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào phân tích hệ thống thực tế. Em nhận ra rằng việc xác định đúng loại sự cố (C, I hay A) là rất quan trọng trước khi đưa ra giải pháp. Phần khó nhất là phân biệt giữa threat và vulnerability vì dễ bị nhầm lẫn. Ngoài ra, em học được cách suy nghĩ có hệ thống khi phân tích rủi ro. Trong thực tế, cần chú ý bảo vệ tính toàn vẹn dữ liệu vì nó ảnh hưởng trực tiếp đến độ tin cậy của hệ thống.
