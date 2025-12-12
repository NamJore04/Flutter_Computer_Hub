# 🛒 E-Commerce App Flutter

Ứng dụng thương mại điện tử (frontend-only) được phát triển bằng Flutter, chuyên về thiết bị máy tính và linh kiện với giao diện người dùng hiện đại và trải nghiệm mua sắm mượt mà.
Link apk: https://drive.google.com/drive/folders/1IKeKTVmxhdTNb9shnwMvRL6uECgR11D0?usp=sharing
Link window: https://drive.google.com/drive/folders/1YFs_tkH0J452ocWzJTufi9t8B230kakT?usp=drive_link

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

## ✨ Tính năng

### 🔥 Tính năng nổi bật
- **Animations & Transitions**: Hiệu ứng chuyển động mượt mà giữa các màn hình
- **Hero Animations**: Hiệu ứng chuyển tiếp liền mạch từ danh sách đến chi tiết sản phẩm
- **Shimmer Loading**: Skeleton loading hiện đại khi tải dữ liệu
- **Swipe-to-delete**: Vuốt để xóa sản phẩm trong giỏ hàng
- **Staggered Animations**: Hiệu ứng xuất hiện tuần tự cho các thành phần UI

### 🛍️ Mua sắm sản phẩm
- Duyệt sản phẩm theo danh mục
- Tìm kiếm và lọc thông minh
- Xem chi tiết sản phẩm với hình ảnh chất lượng cao
- Thêm vào giỏ hàng với hiệu ứng
- Thanh toán đơn hàng đơn giản

### 👤 Quản lý tài khoản
- Đăng ký/đăng nhập bảo mật
- Quản lý thông tin cá nhân
- Theo dõi lịch sử đơn hàng
- Lưu sản phẩm yêu thích

### 🎨 Trải nghiệm người dùng
- Giao diện thân thiện, animations mượt mà
- Chuyển đổi linh hoạt giữa hiển thị dạng lưới và danh sách
- Hỗ trợ Light/Dark mode tự động theo hệ thống

## 🔑 Tính năng khôi phục mật khẩu

Hệ thống khôi phục mật khẩu an toàn qua email với quy trình 2 bước:

### Bước 1: Yêu cầu mã xác nhận
- Nhập email đã đăng ký 
- Nhận mã xác nhận (có hiệu lực 10 phút)
- Email gửi từ: namhuynhfree@gmail.com

### Bước 2: Đặt lại mật khẩu
- Nhập mã xác nhận
- Tạo mật khẩu mới
- Hoàn tất quá trình đặt lại mật khẩu

### ℹ️ Lưu ý kỹ thuật
- **Email**: Sử dụng gói `mailer` với SMTP của Gmail
- **Xử lý lỗi thường gặp**:
  - Kiểm tra thư mục spam
  - Đảm bảo tường lửa cho phép kết nối SMTP
  - Kiểm tra kết nối internet

## 🔧 Công nghệ sử dụng

| Công nghệ | Mục đích |
|-----------|----------|
| **Flutter** | Framework UI đa nền tảng |
| **Provider** | Quản lý state |
| **Shared Preferences** | Lưu trữ dữ liệu cục bộ |
| **Flutter Image Slideshow** | Hiển thị ảnh sản phẩm |
| **Flutter Rating Bar** | Đánh giá sao |
| **Flutter Staggered Animations** | Hiệu ứng xuất hiện cho danh sách |
| **Page Transition** | Hiệu ứng chuyển trang |

## 🚀 Cài đặt và chạy

### Yêu cầu hệ thống
- Flutter SDK (phiên bản mới nhất)
- Dart SDK
- Android Studio/VS Code

### Các bước cài đặt

1. Kiểm tra cài đặt Flutter
```bash
flutter --version
```

2. Clone repository về máy
```bash
git clone https://github.com/NamJore04/Cross-platform-E-commerce-Application.git
```

3. Cài đặt dependencies
```bash
cd ecommerce_app
flutter pub get
```

4. Chạy ứng dụng
```bash
flutter run
```

## 📁 Cấu trúc dự án

```
lib/
  ├── config/          # Cấu hình ứng dụng
  │   ├── animations.dart   # Định nghĩa animations
  │   ├── routes.dart       # Định nghĩa đường dẫn
  │   └── theme.dart        # Cấu hình giao diện
  ├── models/          # Data models
  ├── providers/       # State management
  ├── screens/         # Màn hình ứng dụng
  │   ├── customer/    # Giao diện khách hàng
  │   └── admin/       # Giao diện quản trị
  ├── widgets/         # Thành phần UI có thể tái sử dụng
  └── main.dart        # Entry point
```

## 🤝 Đóng góp

Dự án học tập mở - mọi góp ý và đóng góp đều được hoan nghênh!

1. Fork dự án
2. Tạo nhánh với tính năng (`git checkout -b feature/amazing-feature`)
3. Commit thay đổi (`git commit -m 'Add some amazing feature'`)
4. Push lên nhánh (`git push origin feature/amazing-feature`)
5. Mở Pull Request

## 📝 Giấy phép

Được phân phối theo giấy phép MIT. Xem `LICENSE` để biết thêm thông tin.

---

<div align="center">
  <p>Made with ❤️ by Your Name</p>
</div>
