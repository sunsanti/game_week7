# Adobe Mixamo Unity Project

Dự án mẫu thực hành tích hợp mô hình 3D và hoạt ảnh từ Adobe Mixamo vào Unity Engine.

## 🛠 Thông tin kỹ thuật
- **Unity Version:** `6000.6.1f1` (Unity 6)
- **Render Pipeline:** Universal Render Pipeline (URP)
- **Input System:** Unity Input System (mới)

## 📁 Cấu trúc thư mục quan trọng
- `Assets/Models/`: Chứa mô hình 3D (ví dụ: X Bot, Rigging humanoid)
- `Assets/Animations/`: Chứa các animation FBX tải từ Adobe Mixamo (Idle, Dance, ...)
- `Assets/Controllers/`: Animator Controllers xử lý chuyển đổi trạng thái động tác
- `Assets/Scenes/`: Các Scene chính của dự án

## 🚀 Hướng dẫn mở dự án
1. Clone repository về máy tính:
   ```bash
   git clone <URL_REPOSITORY_CUA_BAN>
   ```
2. Mở **Unity Hub**.
3. Chọn **Add** > **Add project from disk** và trỏ đến thư mục chứa project này.
4. Chọn phiên bản Unity Editor phù hợp (`6000.6.1f1` hoặc phiên bản Unity 6 tương thích) để mở.
5. Unity sẽ tự động tái tạo thư mục `Library` trong lần mở đầu tiên.

## ⚠️ Lưu ý khi làm việc với Git & Unity
- Tuyệt đối **không xóa** hoặc **bỏ sót** các file `.meta` khi commit code và asset.
- Thư mục `Library/`, `Temp/`, `Logs/`, `UserSettings/` đã được cấu hình tự động bỏ qua qua [.gitignore](.gitignore).
