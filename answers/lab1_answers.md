# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Phạm Danh Thái

**MSSV:** 1871020523
**Lớp/Nhóm: CNTT 18-02

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Cơ sở dữ liệu điểm sinh viên
- Asset 2:Tài khoản đăng nhập của giảng viên và sinh viên
- Asset 3 (nếu có): Cơ sở dữ liệu hệ thống

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

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
Viết 5-7 dòng. Qua bài lab này, em hiểu rõ hơn về mô hình CIA trong an ninh thông tin và cách áp dụng vào hệ thống thực tế. Việc xác định assets giúp nhận diện những gì cần bảo vệ quan trọng nhất. Khi phân tích các sự cố theo CIA, em thấy rõ mỗi loại tấn công sẽ ảnh hưởng đến khía cạnh khác nhau của hệ thống. Đặc biệt, việc tìm ra threat, vulnerability và mitigation giúp em hiểu cách hệ thống bị tấn công và cách phòng chống. Điều này rất hữu ích trong việc thiết kế hệ thống an toàn hơn trong tương lai.



## 5. Bonus Flag
A → Confidentiality (C)
B → Integrity (I)
C → Availability (A)

Flag của em: FIT4012{A-C-B-I-C-A}

