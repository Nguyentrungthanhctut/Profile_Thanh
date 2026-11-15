# 💻 ThanhDev-Hub — Interactive 3D Matrix Profile & Bio Card

**ThanhDev-Hub** là trang Profile / Bio cá nhân mang phong cách **Cyberpunk Matrix 3D**, tích hợp hiệu ứng thẻ nghiêng 3D (Tilt), Avatar lật 2 mặt thương hiệu, trình phát nhạc trực quan hóa sóng âm (Audio Visualizer) và kết nối dữ liệu thời gian thực.

![ThanhDev Hub Logo](./logo.jpg)

---

## ✨ Tính năng nổi bật

- **Hiệu ứng 3D Tilt & Nền Matrix:** Thẻ thông tin tự động nghiêng theo chuyển động chuột trên nền mưa ký tự Matrix tối ưu FPS.
- **Avatar 3D Tự Lật (Flip Card):** Vòng tròn trung tâm tự động xoay lật mượt mà mỗi 4 giây (hoặc lật ngay khi chạm/di chuột) giữa ảnh cá nhân (`anh.jpg`) và logo thương hiệu **ThanhDev Hub** (`logo.jpg`).
- **Trình phát nhạc Pro & Web Audio Visualizer:**
  - Sóng âm nhảy theo tần số nhạc thực tế bằng `AudioContext` & HTML5 `<canvas>`.
  - Đầy đủ tính năng: Phát/Tạm dừng (hỗ trợ phím tắt `Space`), chuyển bài, phát ngẫu nhiên (Shuffle), lặp lại 1 bài (Loop), tua tiến độ và điều chỉnh âm lượng.
- **Dữ liệu thời gian thực (Real-time APIs):**
  - Cập nhật đồng hồ thời gian thực và nhiệt độ/thời tiết tại Cần Thơ qua **Open-Meteo API**.
  - Tự động lấy danh sách các dự án mới nhất từ **GitHub API** (`Nguyentrungthanhctut`).
- **Tiện ích mở rộng:** Chuyển đổi giao diện Sáng/Tối (Dark/Light Mode), song ngữ Việt – Anh (`VI / EN`), tạo mã QR chia sẻ trang nhanh và kho lưu trữ Prompt ghi chú.

---

## 📂 Cấu trúc thư mục

Đảm bảo các tệp hình ảnh và âm thanh nằm cùng cấp với `index.html` để trang hoạt động đầy đủ:

```text
ThanhDev-Hub/
├── index.html                  # Mã nguồn giao diện, hiệu ứng 3D & logic JS chính
├── anh.jpg                     # Ảnh đại diện cá nhân (mặt trước Avatar)
├── logo.jpg                    # Logo thương hiệu ThanhDev Hub (mặt sau Avatar & Favicon)
├── nhac.mp3 ... nhac6.mp3      # Danh sách 6 bản nhạc nền MP3
└── README.md                   # Tài liệu giới thiệu dự án
