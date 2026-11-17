<div align="center">
  <img src="logo.jpg" alt="ThanhDev Hub Logo" width="130" height="130" style="border-radius: 50%; border: 3px solid #00ff41;" />
  <h1>🚀 ThanhDev Hub v3.0 PRO — Personal Dashboard & Cloud Workspace</h1>
  <p><strong>Trung tâm điều khiển cá nhân hiệu suất cao, đồng bộ đa thiết bị & bộ công cụ thực chiến dành cho Developer</strong></p>

  ![Status](https://img.shields.io/badge/Status-Active-00ff41?style=flat-square)
  ![Version](https://img.shields.io/badge/Version-3.0%20PRO-00b09b?style=flat-square)
  ![Performance](https://img.shields.io/badge/FPS-Uncapped%20%7C%20144Hz%2B-38bdf8?style=flat-square)
  ![Tech](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-1e293b?style=flat-square)
  ![Author](https://img.shields.io/badge/Author-Nguyễn%20Trung%20Thành-059669?style=flat-square)
</div>

---

**ThanhDev Hub v3.0 PRO** là không gian làm việc và dashboard cá nhân được tối ưu hóa toàn diện về tốc độ khung hình (FPS), đồng bộ dữ liệu đám mây thời gian thực giữa nhiều thiết bị/người truy cập, đi kèm hệ thống công cụ lập trình và quản lý thời gian chuyên sâu.

## ✨ Các Nâng Cấp & Tính Năng Chính (v3.0 PRO)

### 1. ⚡ Tối Ưu Hiệu Năng & Mở Khóa Giới Hạn FPS (Uncapped Engine)
- **Matrix Canvas Engine v3:** Tối ưu hóa GPU với `will-change: transform` và `contain: content`, giảm độ trễ render trên cả PC lẫn Mobile.
- **Tùy chỉnh & Vượt mức FPS:** Cho phép chuyển đổi trực tiếp giữa các chế độ **60 FPS**, **120 FPS**, **144 FPS** và **MAX (Uncapped — chạy tối đa theo tần số quét màn hình)** bằng cách bấm vào ô **System Monitor** ở thẻ trung tâm hoặc gõ lệnh `fps max` trong Terminal.
- **3D Tilt Profile Card & Auto-Flip Logo:** Thẻ thông tin cá nhân nghiêng 3D mượt mà theo chuyển động chuột, kết hợp Avatar tự động lật giữa ảnh cá nhân (`anh.jpg`) và logo thương hiệu (`logo.jpg`).

### 2. ☁️ Dev Utilities & Đồng Bộ Tài Khoản Email Đa Thiết Bị
- **Đánh dấu Email Đã Sử Dụng (Cross-Device Sync):**
  - Tích hợp đồng bộ Cloud JSON thời gian thực (tự cập nhật mỗi 6 giây) kết hợp `localStorage`.
  - Khi bạn hoặc **bất kỳ người truy cập nào trên thiết bị khác** bấm copy (`Mail` / `Cả 2`) hoặc tick chọn, tài khoản đó lập tức được đánh dấu **`ĐÃ DÙNG`** (gạch ngang, đổi màu đỏ, ghi rõ thiết bị và thời gian sử dụng) trên **toàn bộ thiết bị**.
  - Hỗ trợ nút **`Chưa dùng`** để copy hàng loạt chỉ những tài khoản còn mới.
- **Quick Generators:** Tạo nhanh mật khẩu mạnh 16 ký tự, **UUID v4**, và **Unix Timestamp** chỉ với 1 cú click.

### 3. 💻 ThanhDev Terminal OS v3.0 PRO
Giao diện dòng lệnh tích hợp sẵn các tiện ích thực chiến (hỗ trợ phím `↑` / `↓` duyệt lịch sử lệnh):

| Lệnh | Chức năng chi tiết |
| :--- | :--- |
| `help` | Hiển thị danh sách toàn bộ câu lệnh phân loại theo nhóm |
| `readme` | Xem nhanh tài liệu hướng dẫn sử dụng ngay trong Terminal |
| `calc <biểu thức>` | Máy tính biểu thức toán học nhanh (VD: `calc (125 * 8) / 4 + 2^10`) |
| `base64 <text>` | Mã hóa chuỗi sang Base64 và tự động copy vào clipboard |
| `hash <text>` | Băm chuỗi theo chuẩn bảo mật **SHA-256** và tự động copy |
| `ip` | Kiểm tra địa chỉ IP Public, vị trí địa lý và nhà mạng (ISP) |
| `sysinfo` | Xem cấu hình phần cứng trình duyệt (số luồng CPU, RAM, độ phân giải) |
| `fps <60\|120\|144\|max>` | Thiết lập mức giới hạn khung hình cho nền Matrix |
| `pomo <phút>` | Khởi chạy nhanh đồng hồ tập trung Pomodoro với số phút tùy chọn |
| `note <nội dung>` | Thêm nhanh một dòng mới vào khung **Ghi Chú Nhanh** |
| `sync` | Ép đồng bộ lại dữ liệu Cloud ngay lập tức |
| `web` | Liệt kê các dự án web đang hoạt động trên GitHub Pages |
| `matrix` / `theme` | Bật/tắt hiệu ứng Matrix hoặc chuyển đổi **Dark / Light Mode** |
| `clear` | Xóa sạch màn hình Terminal |

### 4. 🔔 Pomodoro Focus — Chuông Báo Thức Đa Hồi Kéo Dài
- **Tùy chỉnh thời gian linh hoạt:** Nhập trực tiếp số phút **Học (1–180p)** và **Nghỉ (1–60p)**, tự động lưu cấu hình.
- **Chuông báo thức công suất lớn:** Sử dụng Web Audio API tạo âm thanh chuông kép tần số cao vang **3 hồi liên tiếp (~5 giây)** kèm hiệu ứng nhấp nháy cảnh báo và nút **Tắt chuông** nhanh.

### 5. 📅 Lịch Tương Tác Theo Ngày & Lịch Sử Truy Cập Live
- **Lịch Tháng & Ghi Chú Từng Ngày:** Bấm vào **bất kỳ ngày nào trên lịch** để ghi lại deadline, lịch học hoặc sự kiện riêng của ngày đó. Các ngày có ghi chú sẽ hiển thị dấu chấm xanh nổi bật.
- **Lịch Sử Truy Cập Toàn Trang (Real-time Tracker):** Tự động bắt và ghi lại mọi thao tác mở liên kết, truy cập dự án, tạo/sử dụng tài khoản trên toàn bộ trang web theo thời gian thực.

### 6. 🎵 Trình Phát Nhạc & Audio Visualizer
- Tích hợp **Web Audio API** hiển thị sóng nhạc theo tần số thực, hỗ trợ phím tắt `Space` để Phát/Tạm dừng, chuyển bài, phát ngẫu nhiên (Shuffle) và lặp lại (Loop).

---

## 📂 Cấu Trúc Thư Mục

```text
ThanhDev-Hub/
├── index.html      # Mã nguồn chính (UI 3 cột, Matrix Engine, Terminal v3.0, Cloud Sync)
├── anh.jpg         # Ảnh đại diện mặt trước
├── logo.jpg        # Logo thương hiệu ThanhDev Hub (README, Avatar mặt sau & Favicon)
├── nhac.mp3        # Danh sách nhạc nền (nhac.mp3 -> nhac6.mp3)
└── README.md       # Tài liệu hướng dẫn sử dụng chi tiết dự án
