# Blog Cá Nhân

Blog tĩnh, không cần server, deploy lên GitHub Pages miễn phí.

## 🚀 Deploy lên GitHub Pages (5 bước)

### Bước 1: Tạo tài khoản GitHub
Vào https://github.com và đăng ký (miễn phí).

### Bước 2: Tạo repository
1. Click nút **New** (dấu +) góc trên bên phải
2. Đặt tên repo: `username.github.io`  
   (thay `username` bằng tên GitHub của bạn, ví dụ: `nguyenvana.github.io`)
3. Chọn **Public**
4. Click **Create repository**

### Bước 3: Upload file
1. Trong trang repo vừa tạo, click **uploading an existing file**
2. Kéo thả toàn bộ thư mục blog vào (hoặc click chọn file)
3. Giữ nguyên cấu trúc folder:
   ```
   index.html
   about.html
   css/style.css
   js/main.js
   posts/bai-viet-1.html
   ```
4. Kéo xuống, click **Commit changes**

### Bước 4: Bật GitHub Pages
1. Vào **Settings** của repo
2. Tìm mục **Pages** (thanh bên trái)
3. Phần Source: chọn **Deploy from a branch**
4. Branch: chọn **main** → **/ (root)**
5. Click **Save**

### Bước 5: Xem blog của bạn!
Sau 1-2 phút, vào địa chỉ:  
`https://username.github.io`

---

## ✏️ Cách thêm bài viết mới

1. Copy file `posts/bai-viet-1.html`
2. Đổi tên thành `posts/bai-viet-moi.html`
3. Sửa nội dung trong thẻ `<article-body>`
4. Thêm card bài viết vào `index.html` (copy 1 khối `<article class="post-card">`)
5. Upload lên GitHub

## 🎨 Tùy chỉnh

- **Tên blog**: Tìm `Nguyễn Văn A` trong tất cả file, thay bằng tên của bạn
- **Màu sắc**: Sửa biến `--accent` trong `css/style.css`
- **Font chữ**: Thay link Google Fonts trong `<head>`

---

Chúc bạn viết vui! ✍️
