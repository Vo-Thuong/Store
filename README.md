# 🛒 Dự án Website Bán Hàng (HTML - CSS - JavaScript)

## Giới thiệu

Dự án này là một **website bán hàng cơ bản** được xây dựng nhằm mục đích học tập và thực hành **HTML, CSS và JavaScript**.  
Website mô phỏng quy trình mua sắm trực tuyến với các tính năng cơ bản như:

- Hiển thị sản phẩm
- Thêm sản phẩm vào giỏ hàng
- Quản lý giỏ hàng
- Giao diện quản trị (admin) để quản lý người dùng và sản phẩm

Dự án được thiết kế đơn giản, dễ hiểu, dễ mở rộng và có thể làm nền tảng để phát triển các hệ thống thương mại điện tử lớn hơn.

---

## Cấu trúc thư mục

javascrip/
│── index.html # Trang chủ
│── cart.html # Trang giỏ hàng
│
├── admin/
│ ├── index.html # Giao diện quản trị (dashboard)
│ └── index-user.html # Trang quản lý người dùng
│
├── css/
│ ├── style.css # CSS chính cho website
│ ├── style-user.css # CSS riêng cho phần người dùng
│ ├── style-admin.css # CSS riêng cho phần quản trị
│ ├── styles-admin.css # CSS bổ sung cho admin
│ └── style-1.css # File CSS phụ
│
├── img/ # Thư mục chứa hình ảnh
│ ├── logo.png
│ ├── banner-1.jpg
│ ├── banner-2.jpg
│ ├── banner-3.jpg
│ └── …  
│
├── js/ # Thư mục javascript
│ ├── admin-user.js # js cho phần thông tin của user
│ ├── admin.js # js cho phần admin
│ ├── control.js # js cho phần mua hàng
│ ├── product.js # js cho phần hiển thị thông tin hàng
│ └──script.js # js chung bỏ sung cho toàn bộ bài
└──user.js # js cho phần người dùng
│
├── search/ # Thư mục timg kiếm
│ ├── search.html
│
├── user/ # Thư mục user
│ ├── info.html #thông tin người dùng
│ ├── signin.html.html #đăng ký
│ └── signup.html #đăng nhập
│
│
└── .vscode/settings.json # Cấu hình hỗ trợ cho Visual Studio Code

---

## Cách chạy dự án

1. Tải hoặc clone project về máy:
   ```bash
   git clone <repository-url>
   ```
2. Mở thư mục dự án bằng VS Code hoặc bất kỳ IDE nào.
3. Chạy trực tiếp bằng cách mở file index.html trong trình duyệt (Chrome, Edge, Firefox…).
4. Truy cập các trang chính:
   Trang chủ: index.html
   Giỏ hàng: cart.html
   Quản trị: admin/index.html
   Quản lý người dùng: admin/index-user.html

Dành cho người dùng
Xem danh sách sản phẩm.
Thêm sản phẩm vào giỏ hàng.
Xem và chỉnh sửa giỏ hàng.
Giao diện thân thiện, dễ sử dụng.

Dành cho Admin
Trang quản trị riêng biệt.
Quản lý danh sách người dùng.
Quản lý sản phẩm (mẫu cơ bản).
Giao diện quản trị có CSS riêng biệt.

Giao diện & Trải nghiệm
Giao diện chia rõ ràng cho người dùng và admin.
Sử dụng nhiều file CSS để dễ quản lý và chỉnh sửa.
Thiết kế responsive cơ bản (tương thích trên nhiều màn hình).
Hình ảnh minh họa sản phẩm và banner trực quan.
