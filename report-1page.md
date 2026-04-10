# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Student grade database
- Login credentials
- 

**CIA mapping:**
- Sự cố A -> Confidentiality (lộ điểm sinh viên cho người không có quyền)
- Sự cố B -> Integrity (điểm bị sửa trái phép)
- Sự cố C -> Availability (hệ thống bị sập, không truy cập được)
**Phân tích sự cố B:**
- Threat: Hacker hoặc sinh viên truy cập trái phép để thay đổi điểm.
- Vulnerability:Mật khẩu yếu hoặc bị lộ; không có phân quyền rõ ràng; thiếu cơ chế ghi log
- Mitigation:Sử dụng xác thực mạnh (mật khẩu + OTP); phân quyền rõ ràng; ghi log và kiểm tra lịch sử

### 4. Kết luận ngắn
Qua bài lab này, em đã hiểu rõ hơn về mô hình CIA (Confidentiality, Integrity, Availability) trong an ninh thông tin và cách áp dụng chúng vào các hệ thống thực tế. Việc xác định assets giúp em nhận diện được những tài sản quý giá cần được ưu tiên bảo vệ. Khi phân tích các sự cố theo mô hình CIA, em thấy rõ mỗi loại hình tấn công sẽ gây ra những ảnh hưởng khác nhau tới hệ thống. Việc tìm ra threat, vulnerability và đề xuất mitigation giúp em có cái nhìn tổng quan về cách phòng thủ. Những kiến thức này thực sự rất hữu ích cho việc thiết kế và vận hành các hệ thống an toàn trong tương lai.
