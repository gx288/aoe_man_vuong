# AoE Màn Vuông - Sửa lỗi co giãn màn hình AoE 1 (Age of Empires: Rise of Rome)

Bộ công cụ biên dịch đồ họa (wrapper) dựa trên **cnc-ddraw** được cấu hình sẵn, giúp sửa lỗi game **AoE 1 bị giãn tràn màn hình (16:9)** trên các màn hình rộng hiện đại sử dụng kết nối Analog/VGA cũ. Bộ công cụ giúp đưa game về hiển thị chuẩn tỷ lệ vuông 4:3 cổ điển (tự động thêm 2 viền đen ở hai bên màn hình khi chơi Fullscreen) và tối ưu hóa hiệu năng trên Windows 10/11.

---

## ✨ Tính năng chính

- 📺 **Giữ nguyên tỷ lệ 4:3 gốc (Pillarboxing):** Tự động thêm 2 khoảng đen ở hai bên màn hình khi chơi ở chế độ Fullscreen, loại bỏ hoàn toàn hiện tượng giãn dẹt hình ảnh (lùn nhà, bẹt quân).
- 🚀 **Tăng tốc phần cứng (Hardware Acceleration):** Dịch các lệnh đồ họa 2D cổ điển (DirectDraw) sang Direct3D 9 hoặc OpenGL hiện đại, giúp game chạy ổn định và mượt mà hơn trên GPU.
- 🖱️ **Sửa lỗi giật chuột (Fix Mouse Lag):** Khắc phục triệt để hiện tượng con trỏ chuột bị khựng, giật hoặc không chính xác khi chơi AoE trên Windows 10/11.
- 🍃 **Siêu nhẹ & An toàn:** Dung lượng siêu nhỏ (chưa tới 5MB), không chiếm dụng tài nguyên hệ thống và không chứa mã độc.

---

## 🛠️ Hướng dẫn cài đặt (Chỉ cần làm 1 lần duy nhất)

1. **Tải về hoặc Clone repository này.**
2. **Sao chép (Copy) toàn bộ các file bên dưới:**
   - Thư mục `Shaders`
   - File `cnc-ddraw config.exe`
   - File `ddraw.dll`
   - File `ddraw.ini`
3. **Dán đè (Paste) vào thư mục cài đặt game AoE của bạn.**
   - *Đường dẫn mặc định trên XArena thường là:* `C:\Program Files (x86)\XArena\Game\AOE1R`
   - *Nếu Windows yêu cầu quyền Administrator, bạn chỉ cần chọn **Continue (Tiếp tục)** để đồng ý.*

---

## 🎮 Cách sử dụng

Sau khi dán đè xong, bạn không cần phải mở hay chạy thêm bất kỳ công cụ phụ trợ nào khác:
- Cứ khởi động game thông qua **XArena**, **EGOPlay** hoặc chạy trực tiếp file game (`Empiresx.exe`, `Empiresx_r.exe`, v.v...) bình thường.
- Game sẽ tự động nhận diện thư viện và hiển thị chuẩn tỷ lệ vuông 4:3 có viền đen ở 2 bên một cách hoàn hảo!

---

## 🌟 Lời cảm ơn (Credits)
Bộ công cụ này sử dụng mã nguồn mở của dự án **cnc-ddraw** được phát triển bởi **FunkyFr3sh**.
- Chi tiết dự án gốc tại: [GitHub - FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw)

---
Chúc các bạn chơi game vui vẻ và có những trận chiến rực rỡ! 🎮🔥
