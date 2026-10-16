# Game Week 7 – Mixamo trong Unity

Project thực hành đưa nhân vật 3D và chuyển động lấy từ Adobe Mixamo vào Unity.

## 🛠 Môi trường phát triển
- **Phiên bản Unity:** `6000.6.1f1` (Unity 6)
- **Pipeline đồ họa:** Universal Render Pipeline (URP)
- **Xử lý input:** Input System thế hệ mới của Unity

## 📁 Các thư mục chính
- `Assets/Models/`: mô hình nhân vật 3D (như X Bot, rig humanoid)
- `Assets/Animations/`: file FBX animation tải về từ Mixamo (Idle, Dance, ...)
- `Assets/Controllers/`: Animator Controller điều khiển việc chuyển qua lại giữa các động tác
- `Assets/Scenes/`: các Scene chính của project

## 🚀 Cách mở project
1. Tải source code về máy:
   ```bash
   git clone https://github.com/sunsanti/game_week7.git
   ```
2. Khởi động **Unity Hub**.
3. Bấm **Add** > **Add project from disk**, rồi chọn thư mục vừa clone.
4. Mở bằng Unity Editor `6000.6.1f1` (hoặc một bản Unity 6 tương thích).
5. Ở lần mở đầu, Unity sẽ tự build lại thư mục `Library`, nên có thể hơi lâu.

## ⚠️ Lưu ý khi dùng Git với Unity
- Khi commit code hoặc asset, luôn commit kèm file `.meta` tương ứng, **không được xóa hay bỏ qua** chúng.
- Các thư mục `Library/`, `Temp/`, `Logs/`, `UserSettings/` đã nằm trong [.gitignore](.gitignore) nên Git sẽ không theo dõi.
