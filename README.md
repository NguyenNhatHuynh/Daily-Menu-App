# Ứng Dụng Thực Đơn Hàng Ngày 🍽️

Ứng dụng **"Thực Đơn Hàng Ngày"** cung cấp thực đơn món ăn hàng ngày, kèm theo công thức nấu ăn chi tiết và các gợi ý chế độ ăn uống phù hợp với các nhu cầu dinh dưỡng khác nhau. Ứng dụng giúp người dùng dễ dàng tìm kiếm, lưu trữ thực đơn yêu thích và theo dõi các mục tiêu dinh dưỡng như giảm cân, tăng cân hoặc duy trì sức khỏe.

## Mục Tiêu 🎯

- Cung cấp thực đơn món ăn mỗi ngày với các mục tiêu dinh dưỡng khác nhau (ăn kiêng, giảm cân, ăn uống lành mạnh).
- Cung cấp công thức nấu ăn chi tiết cho từng món, bao gồm nguyên liệu, cách chế biến và thời gian nấu.
- Giúp người dùng dễ dàng tìm kiếm các món ăn theo nguyên liệu hoặc loại món ăn.
- Hỗ trợ người dùng theo dõi lượng calo, protein, carbs cho mỗi món ăn.
- Hỗ trợ chế độ ăn uống đặc biệt như chế độ ăn kiêng, ăn chay, kiêng gluten, v.v.

## Các Tính Năng Chính 🛠️

- **Trang chủ** 🏠: Hiển thị thực đơn món ăn hàng ngày với các mục tiêu dinh dưỡng khác nhau (ăn kiêng, tăng cân, giảm cân, ăn uống lành mạnh, v.v).
- **Công thức nấu ăn** 🍳: Cung cấp chi tiết công thức nấu ăn cho từng món, bao gồm nguyên liệu, cách chế biến, và thời gian nấu.
- **Lựa chọn chế độ ăn uống** 🥗: Người dùng có thể chọn chế độ ăn uống phù hợp với nhu cầu của mình (kiêng đường, kiêng gluten, chế độ ăn chay, v.v.).
- **Lưu trữ thực đơn** 💾: Người dùng có thể lưu lại các thực đơn yêu thích hoặc tạo thực đơn cá nhân cho các ngày khác.
- **Tìm kiếm món ăn** 🔍: Cho phép tìm kiếm món ăn theo nguyên liệu hoặc loại món ăn.
- **Chế độ theo dõi dinh dưỡng** 🍏: Cung cấp thông tin về lượng calo, protein, carbs cho mỗi món ăn.

## Cấu Trúc Dự Án 📁

Dự án sử dụng Flutter để phát triển ứng dụng di động với cấu trúc thư mục rõ ràng và dễ quản lý. Các phần chính trong dự án bao gồm:

- **models/**: Chứa các mô hình dữ liệu (Meal, Recipe, User).
- **screens/**: Các màn hình của ứng dụng (Home, Meal Detail, Login, Register, Profile).
- **components/**: Các widget tùy chỉnh như button, app bar, meal card.
- **network/**: Quản lý các yêu cầu API để lấy thực đơn, công thức và thông tin người dùng.
- **state_management/**: Quản lý trạng thái của ứng dụng sử dụng Provider/Riverpod.
- **utils/**: Các hàm tiện ích như định dạng ngày tháng, validation form.

## Công Nghệ Sử Dụng ⚙️

- **Flutter**: Framework để phát triển ứng dụng di động.
- **Dio**: Thư viện để thực hiện các yêu cầu HTTP.
- **Provider** hoặc **Riverpod**: Quản lý trạng thái.
- **Firebase Authentication**: Đăng nhập và đăng ký người dùng.
- **SQLite**: Lưu trữ dữ liệu cục bộ (lưu trữ thực đơn yêu thích, công thức, v.v.).

## Hướng Dẫn Cài Đặt 🛠️

### Điều Kiện

Đảm bảo bạn đã cài đặt những phần mềm sau trên máy của mình:
- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart SDK: Included with Flutter
- Android Studio (for Android development)
- Visual Studio Code or any other IDE
  
1. Clone dự án về máy của bạn:
   ```bash
   git clone https://github.com/NguyenNhatHuynh/Daily-Menu-App.git

2. **Navigate to the project directory**
    ```bash
    cd daily_menu_app

3. **Install dependencies**
    ```bash
    flutter pub get

4. **Run the application**
    ```bash
    flutter run

---

## Ảnh giao diện

# Tác giả👨‍💻
### Tôi sẽ rất cảm kích nếu bạn có thể cho kho lưu trữ này một ngôi sao 🌟. Nó sẽ giúp những người khác khám phá ra điều này. Cảm ơn vì sự hỗ trợ của bạn [Xoan Dev]👨‍💻
- [x] status Project: Pending
