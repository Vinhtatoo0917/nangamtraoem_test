# Hướng Dẫn Kích Hoạt GitHub Pages Cho Dự Án

Trang web được tổ chức tối ưu theo chuẩn GitHub Pages:
- `index.html` nằm tại thư mục gốc (root) để GitHub Pages tự động nhận diện trang chủ.
- Toàn bộ file định dạng giao diện nằm trong `assets/css/style.css`.
- Tài nguyên hình ảnh lưu trữ trong `assets/images/`.

### Các bước đẩy mã nguồn lên GitHub:

1. Mở Terminal tại thư mục dự án:
```bash
git init
git add .
git commit -m "Cau truc thu muc nang-am-trao-em"
```

2. Liên kết với Repository GitHub của bạn:
```bash
git branch -M main
git remote add origin https://github.com/<tai-khoan-github-cua-ban>/<ten-repository>.git
git push -u origin main
```

3. Bật GitHub Pages:
- Vào **Settings** trên repo GitHub -> chọn **Pages**.
- Tại phần **Branch**, chọn **`main`** và thư mục **`/ (root)`** -> Nhấn **Save**.
- Sau 1-2 phút, GitHub sẽ cấp link website trực tuyến hoạt động 100%.

