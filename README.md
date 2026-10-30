# CozySMP Website

Landing page giới thiệu Minecraft server CozySMP — Survival for fun.

## Chạy thử
Mở `index.html` bằng trình duyệt hoặc dùng VS Code Live Server.

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub (ví dụ `cozysmp-website`).
2. Upload `index.html` lên thư mục gốc của repository.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch** → branch `main` → folder `/ (root)` → **Save**.
5. Chờ GitHub Pages deploy xong. Website sẽ có địa chỉ dạng `https://TEN-USER.github.io/cozysmp-website/`.

## Cấu hình
- IP hiển thị: `cozysmp.io.vn` (trong HTML).
- Live player count: lấy từ API công khai `https://api.mcstatus.io/v2/status/java/cozysmp.io.vn`, tự cập nhật mỗi 30 giây.
- Nếu server của bạn là Bedrock, cần đổi endpoint `/java/` thành `/bedrock/`.
- Hình nền dùng ảnh Unsplash nên cần internet để tải ảnh.
