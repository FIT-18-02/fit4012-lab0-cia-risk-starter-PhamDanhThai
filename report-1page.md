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
- Cơ sở dữ liệu điểm sinh viên  
- Tài khoản đăng nhập của giảng viên và sinh viên 

**CIA mapping:**

- Sự cố A: Sinh viên xem được điểm của người khác → **Confidentiality**  
- Sự cố B: Điểm bị sửa trái phép → **Integrity**  
- Sự cố C: Hệ thống bị sập, không truy cập được → **Availability**
- 
**Phân tích sự cố B:**
- Threat: Hacker hoặc người dùng nội bộ chỉnh sửa điểm trái phép  
- Vulnerability:  - Không kiểm tra phân quyền chặt chẽ  
  - Không có cơ chế log hoặc xác thực thay đổi dữ liệu 
- Mitigation:
- - Áp dụng phân quyền (Role-Based Access Control)  
  - Ghi log tất cả thay đổi dữ liệu  
  - Sử dụng xác thực 2 lớp (2FA)  
  - Mã hóa và kiểm tra tính toàn vẹn dữ liệu 

### 4. Kết luận ngắn

Qua bài lab, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào phân tích rủi ro trong hệ thống thực tế. Em học được cách xác định tài sản, phân loại sự cố và đề xuất biện pháp bảo mật phù hợp. Phần khó nhất là phân biệt chính xác giữa threat và vulnerability trong từng tình huống. Khi phân tích sự cố an toàn thông tin, cần chú ý đến quyền truy cập, kiểm soát dữ liệu và khả năng hệ thống bị gián đoạn. Điều này giúp đảm bảo hệ thống hoạt động an toàn và hiệu quả hơn.
