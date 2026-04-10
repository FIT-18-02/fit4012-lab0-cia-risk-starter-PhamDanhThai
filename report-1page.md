# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản (Assets) cần bảo vệ trong hệ thống thông tin.
- Hiểu và phân biệt bộ ba: Confidentiality (Bảo mật), Integrity (Toàn vẹn), Availability (Sẵn sàng).
- Phân tích mối liên hệ giữa Threat (Mối đe dọa), Vulnerability (Lỗ hổng) và Mitigation (Biện pháp giảm thiểu).
- Thành thạo quy trình làm việc trên GitHub (Clone, Commit, Push).

### 2. Cách làm
- Phân tích bối cảnh hệ thống quản lý điểm để xác định các thành phần nhạy cảm.
- Áp dụng mô hình CIA để phân loại các rủi ro tiềm tàng.
- Thực hiện kỹ thuật phân tích rủi ro cho sự cố sửa đổi dữ liệu (Integrity).
- Sử dụng Git để quản lý phiên bản và nộp bài tự động qua GitHub Actions.

### 3. Kết quả chính
**Assets:**
- Student grade database (Cơ sở dữ liệu điểm).
- Login credentials (Thông tin đăng nhập của giảng viên/sinh viên).
- System Infrastructure (Hạ tầng máy chủ và mã nguồn hệ thống).

**CIA Mapping:**
- **Sự cố A -> Confidentiality:** Lộ điểm sinh viên cho người không có thẩm quyền.
- **Sự cố B -> Integrity:** Điểm số bị thay đổi trái phép, làm mất tính chính xác.
- **Sự cố C -> Availability:** Hệ thống bị tấn công từ chối dịch vụ (DoS), không thể truy cập để tra cứu.

**Phân tích sự cố B (Tính toàn vẹn):**
- **Threat:** Hacker bên ngoài hoặc người dùng nội bộ lạm quyền để thay đổi kết quả học tập.
- **Vulnerability:** Hệ thống quản lý phiên đăng nhập lỏng lẻo; mật khẩu yếu; thiếu kiểm tra đầu vào (Input Validation).
- **Mitigation:** Triển khai xác thực 2 lớp (2FA); áp dụng nguyên tắc đặc quyền tối thiểu (Least Privilege); bật tính năng Auditing (ghi nhật ký thay đổi dữ liệu).

### 4. Kết luận
Bài lab đã giúp em chuyển đổi từ lý thuyết an ninh mạng sang tư duy phân tích thực tế. Việc hiểu rằng an toàn thông tin không chỉ là "chống hack" mà là bảo vệ cả 3 khía cạnh C-I-A giúp em có cái nhìn toàn diện hơn khi thiết kế hoặc vận hành bất kỳ hệ thống phần mềm nào trong tương lai.
