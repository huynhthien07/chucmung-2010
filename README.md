# Thư Hồng 20.10

Trang chúc mừng Ngày Phụ nữ Việt Nam 20/10: người xem nhập tên, mở hộp quà, ngắm đóa hồng pha lê 3D (kéo để xoay, chạm để hoa tỏa sáng) và đọc một lá thư tay được chọn ngẫu nhiên, ký tên **Nguyễn Thế Việt**.

## Cấu trúc

- `index.html`: toàn bộ trang (HTML, CSS, JavaScript, cảnh 3D dùng Three.js r128 tải từ cdnjs).
- `nhac.mp3`: nhạc nền. Nếu file không tải được, trang tự dùng nhạc hộp nhạc tạo bằng Web Audio.

## Chỉnh nội dung

Mở `index.html`, tìm `const CONFIG`:

- `sender`: tên người gửi, luôn đứng cuối mỗi lá thư.
- `letters`: các lá thư. `{ten}` là tên gọi (chữ cuối của tên đã nhập), `{name}` là họ tên đầy đủ.
- `musicUrl`: tên file nhạc nền đặt cạnh `index.html`.

## Gửi link có sẵn tên

Thêm `?ten=` vào cuối link, ví dụ `https://<trang-cua-ban>/?ten=Mai`. Mở ra là ô tên đã được điền "Mai".

## Chạy thử trên máy

```bash
python -m http.server 8765
```

Rồi mở `http://localhost:8765`.
