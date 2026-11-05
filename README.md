# Chiến Dịch Thiện Nguyện: NẮNG ẤM TRAO EM

> **"Góp chút nắng vàng, thắp ngàn ước mơ"**

Website Landing Page từ thiện trẻ em vùng cao Việt Nam được xây dựng theo phong cách hiện đại, cảm xúc và tương thích hoàn hảo 100% với **GitHub Pages** (Chỉ dùng **HTML5 & CSS3 thuần**, không phụ thuộc JavaScript).

---

## Tính Năng Nổi Bật

1. **Dual Action Form (Thuần CSS Tabs)**:
   - **Tab 1 - Góp Quỹ / Ủng Hộ Tài Chính**: Tích hợp các gói tiền đóng góp mẫu (100k, 250k, 500k, 1tr), form thông tin ủng hộ, ẩn danh, và **mã VietQR tự động** kèm số tài khoản ngân hàng rõ ràng.
   - **Tab 2 - Đăng Ký Đi Tình Nguyện Viên Vùng Cao**: Form đăng ký chi tiết (năm sinh, nơi xuất phát, các đợt đi Lũng Cú, Xín Mần, Mường Nhé, Sơn La, checkbox chọn kỹ năng đóng góp) kèm lịch trình cụ thể của chuyến đi.
   - Chuyển đổi giữa 2 form linh hoạt bằng kỹ thuật CSS Radio `:checked`.
2. **Minh Bạch Tài Chính 100%**:
   - Bảng sao kê giao dịch thời gian thực mô phỏng trực quan, tạo niềm tin lớn cho các nhà hảo tâm.
3. **Pure CSS Accordion (FAQ)**:
   - Các câu hỏi thường gặp có thể đóng/mở mượt mà không cần bất kỳ dòng JavaScript nào.
4. **Pure CSS Mobile Navigation Hamburger**:
   - Menu responsive tự động co giãn đẹp mắt trên điện thoại, máy tính bảng và desktop.
5. **Thiết Kế Hiện Đại & Tươi Sáng**:
   - Gam màu cam ấm áp và vàng nắng, kết hợp typography `Plus Jakarta Sans` chuẩn UX/UI hiện đại.

---

## Hướng Dẫn Push Lên GitHub & Kích Hoạt GitHub Pages

Để đưa trang web hoạt động online miễn phí trên GitHub Pages:

### Bước 1: Khởi tạo Git và Commit
Mở terminal (PowerShell hoặc Git Bash) tại thư mục này:
```bash
git init
git add .
git commit -m "Khoi tao website Nang Am Trao Em"
```

### Bước 2: Tạo Repository trên GitHub và Đẩy Lên
1. Đăng nhập vào [GitHub](https://github.com) -> Tạo một repository mới (ví dụ: `nang-am-trao-em`).
2. Chạy lệnh:
```bash
git branch -M main
git remote add origin https://github.com/<tai-khoan-cua-ban>/nang-am-trao-em.git
git push -u origin main
```

### Bước 3: Bật GitHub Pages
1. Vào repository trên GitHub -> Click chọn tab **Settings**.
2. Tìm đến mục **Pages** ở thanh menu bên trái.
3. Ở phần **Build and deployment** -> **Branch**: chọn `main` và thư mục `/ (root)` -> bấm **Save**.
4. Chờ 1 - 2 phút, GitHub sẽ cung cấp link trang web công khai có dạng:
   `https://<tai-khoan-cua-ban>.github.io/nang-am-trao-em/`

