# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Phạm Danh Thái

**MSSV:** 1871020523
**Lớp/Nhóm:** CNTT 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Cơ sở dữ liệu điểm sinh viên
- Asset 2:Tài khoản đăng nhập của giảng viên và sinh viên
- Asset 3 (nếu có):

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Sinh viên xem được điểm của người khác → Confidentiality
- Sự cố B -> Điểm bị sửa trái phép → Integrity
- Sự cố C -> Hệ thống bị sập, không truy cập được → Availability

---

## 3. Phân tích sự cố B
- Threat: Hacker hoặc người dùng nội bộ chỉnh sửa điểm trái phép
- Vulnerability: -Không kiểm tra phân quyền chặt chẽ
                 -Không có cơ chế log hoặc xác thực thay đổi dữ liệu
- Mitigation:
Áp dụng phân quyền (Role-based access control)
Ghi log tất cả thay đổi dữ liệu
Sử dụng xác thực 2 lớp (2FA)
Mã hóa và kiểm tra tính toàn vẹn dữ liệu
---

## 4. Reflection
Qua bài lab này, em hiểu rõ hơn về mô hình CIA gồm Confidentiality, Integrity và Availability trong bảo mật hệ thống. Việc xác định tài sản cần bảo vệ là bước quan trọng để đánh giá rủi ro. Ngoài ra, em nhận thấy mỗi sự cố đều liên quan đến một yếu tố trong CIA và cần có biện pháp phù hợp để giảm thiểu rủi ro. Bài lab cũng giúp em hiểu rõ hơn về mối quan hệ giữa threat, vulnerability và mitigation. Đây là nền tảng quan trọng để thiết kế hệ thống an toàn trong thực tế.



---

## 5. Bonus Flag
A → Confidentiality (C)
B → Integrity (I)
C → Availability (A)

Flag của em: FIT4012{A-C-B-I-C-A}

