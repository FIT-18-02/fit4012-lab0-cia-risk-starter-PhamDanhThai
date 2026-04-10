# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
-Hiểu và áp dụng mô hình CIA (Confidentiality, Integrity, Availability) để phân tích rủi ro trong hệ thống lưu trữ điểm.

### 2. Cách làm
- Xác định các tài sản quan trọng trong hệ thống  
- Phân loại các sự cố theo mô hình CIA  
- Phân tích một sự cố cụ thể (Threat, Vulnerability, Mitigation)  
- Tổng hợp và rút ra kết luận  

### 3. Kết quả chính
**Assets:**
- Xác định được các assets quan trọng  
- Phân loại chính xác các sự cố theo CIA  
- Đề xuất các biện pháp giảm thiểu rủi ro phù hợp  

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
