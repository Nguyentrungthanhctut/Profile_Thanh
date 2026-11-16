<div align="center">
  <img src="logo.jpg" alt="ThanhDev Hub Logo" width="130" height="130" style="border-radius: 50%; border: 3px solid #00ff41;" />
  <h1>🚀 ThanhDev Hub — Personal Dashboard & Developer Workspace</h1>
  <p><strong>Trung tâm điều khiển cá nhân, công cụ lập trình & không gian học tập phong cách Matrix Cyberpunk</strong></p>

  ![Status](https://img.shields.io/badge/Status-Active-00ff41?style=flat-square)
  ![Version](https://img.shields.io/badge/Version-2.6-00b09b?style=flat-square)
  ![Tech](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-1e293b?style=flat-square)
  ![Author](https://img.shields.io/badge/Author-Nguyễn%20Trung%20Thành-059669?style=flat-square)
</div>

---

**ThanhDev Hub** là trang Dashboard cá nhân tích hợp bộ công cụ tiện ích dành cho lập trình viên và học tập, thiết kế theo phong cách **Matrix Cyberpunk Glassmorphism** với bố cục 3 cột đối xứng, tương thích mượt mà trên mọi kích thước màn hình (Desktop, Tablet, Mobile).

## ✨ Tính Năng Nổi Bật

### 1. 🖥️ Bố Cục & Giao Diện (UI/UX)
- **Bố cục 3 cột cân đối (Symmetric 3-Column Grid):** Tự động co giãn thông minh trên Desktop, chia 2 cột song song trên Tablet và xếp dọc gọn gàng trên Mobile.
- **Matrix Rain Engine:** Hiệu ứng mưa ký tự nền Canvas 60 FPS, hỗ trợ tạm dừng (`matrix`) hoặc chuyển đổi sang **Light Mode**.
- **3D Tilt Profile Card:** Thẻ thông tin cá nhân trung tâm phản hồi nghiêng 3D theo chuyển động chuột, kèm Avatar 2 mặt tự động lật giữa ảnh cá nhân (`anh.jpg`) và logo (`logo.jpg`).
- **Đa ngôn ngữ (VI / EN) & Thời tiết Real-time:** Cập nhật nhiệt độ và trạng thái thời tiết tại **Cần Thơ, VN** qua Open-Meteo API cùng đồng hồ thời gian thực.

### 2. 💻 ThanhDev Terminal (Interactive CLI)
Giao diện dòng lệnh mô phỏng Bash ngay trên trình duyệt, hỗ trợ phím mũi tên `↑` / `↓` để gọi lại lịch sử lệnh:
- `help` — Hiển thị danh sách toàn bộ lệnh hỗ trợ.
- `readme` — Mở hướng dẫn sử dụng chi tiết từng module ngay trong Terminal (hỗ trợ `readme pomo`, `readme dev`, `readme music`, `readme shortcuts`).
- `web` — Liệt kê nhanh các trang web đang chạy Live trên GitHub Pages.
- `contact` — Xem thông tin liên hệ, trường học (CTUT) và các kênh mạng xã hội.
- `matrix` — Bật / tạm dừng hiệu ứng nền Matrix để tiết kiệm pin.
- `theme` — Chuyển đổi nhanh giữa **Dark Matrix** và **Light Mode**.
- `clear` — Xóa sạch màn hình Terminal.

### 3. 🛠️ Dev Utilities (Công Cụ Lập Trình & Tạo Acc Clone)
- **Quick Generators:** Tạo nhanh mật khẩu mạnh 16 ký tự, **UUID v4**, và **Unix Timestamp** chỉ với 1 cú click.
- **Tạo hàng loạt Email Clone (`@gmail.com`):**
  - Tùy chọn số lượng tài khoản cần tạo từ **1 đến 50 acc**.
  - Tự động sinh tên tiếng Việt không dấu tự nhiên kèm mật khẩu mạnh riêng cho từng tài khoản.
  - Hỗ trợ nút **Copy từng thành phần** (`Mail`, `Pass`, `Cả 2` định dạng `email|pass`) hoặc **Copy All** toàn bộ danh sách.

### 4. ⏱️ Pomodoro Focus (Học Tập & Làm Việc)
- **Tùy chỉnh thời gian linh hoạt:** Nhập trực tiếp số phút **Học (1–180p)** và **Nghỉ (1–60p)**, tự động lưu cấu hình vào `localStorage`.
- **Không tự bật nhạc nền:** Giữ không gian yên tĩnh tuyệt đối khi đếm giờ.
- **Chuông báo thức "Ting Ting" (Web Audio API):** Tự động phát âm thanh chuông đôi trong trẻo khi hết phiên học/nghỉ (không cần file `.mp3` ngoài), có sẵn nút test chuông ngay góc widget.

### 5. 🎵 Trình Phát Nhạc & Audio Visualizer
- Tích hợp **Web Audio API** vẽ sóng nhạc theo tần số thời gian thực.
- Đầy đủ chức năng: Phát/Tạm dừng (`Space`), Chuyển bài, Phát ngẫu nhiên (Shuffle), Lặp lại 1 bài (Loop), Thanh tua và Điều chỉnh âm lượng.

### 6. 📅 Tiện Ích Quản Lý Cá Nhân
- **Live Web Showcase:** Tự động quét và hiển thị các dự án đã bật **GitHub Pages** từ tài khoản `Nguyentrungthanhctut`.
- **Lịch Sử Truy Cập Tự Động:** Ghi lại thời gian và liên kết các trang vừa mở, lưu trữ cục bộ trên trình duyệt.
- **Lịch Tháng Mini & Ghi Chú Nhanh:** Xem lịch tháng trực quan và ghi chú tự động lưu (Auto-save) không lo mất dữ liệu khi tải lại trang.

---

## 📂 Cấu Trúc Thư Mục

```text
ThanhDev-Hub/
├── index.html      # Mã nguồn chính (HTML + CSS + JS tích hợp)
├── anh.jpg         # Ảnh đại diện mặt trước
├── logo.jpg        # Logo thương hiệu ThanhDev Hub (hiển thị ở README, Avatar mặt sau & Favicon)
├── nhac.mp3        # Danh sách nhạc nền (nhac.mp3 -> nhac6.mp3)
└── README.md       # Tài liệu hướng dẫn sử dụng dự án
