🎵 BKMusic


BKMusic là một website nghe nhạc đơn giản được phát triển bằng PHP, HTML, CSS và MySQL, cho phép người dùng nghe nhạc trực tuyến, quản lý playlist, tìm kiếm bài hát và quản lý tài khoản cá nhân.

🚀 Tính năng chính
🎧 Nghe nhạc online trực tiếp từ trình duyệt

🔎 Tìm kiếm bài hát theo tên, nghệ sĩ hoặc thể loại

❤️ Thêm bài hát vào playlist yêu thích

👤 Đăng ký / Đăng nhập người dùng

🔒 Quản lý tài khoản, bảo mật bằng mật khẩu mã hóa

🛠️ Trang admin quản lý bài hát, thể loại và người dùng (tuỳ chọn)

🛠️ Công nghệ sử dụng

Công nghệ	Mô tả
PHP	Xử lý logic phía server
HTML/CSS	Giao diện người dùng
MySQL	Cơ sở dữ liệu lưu trữ bài hát, user, playlist...
XAMPP / MAMP / LAMP	Chạy server PHP và MySQL cục bộ

📦 Cài đặt và chạy dự án
Yêu cầu
PHP >= 7.x

MySQL Server

Trình duyệt web (Chrome, Firefox...)

XAMPP / MAMP hoặc tương đương

Các bước cài đặt
Clone dự án về máy:

bash
Sao chép
Chỉnh sửa
git clone https://github.com/your-username/BKMusic.git
Import CSDL:

Mở phpMyAdmin

Tạo database mới (ví dụ: bkmusic)

Import file database.sql vào

Cấu hình kết nối CSDL trong includes/connect.php:

php
Sao chép
Chỉnh sửa
$host = "localhost";
$username = "root";
$password = ""; // hoặc mật khẩu MySQL của bạn
$database = "bkmusic";
$conn = new mysqli($host, $username, $password, $database);
Chạy dự án trên localhost:

Đặt thư mục vào htdocs (XAMPP) hoặc www (MAMP)

Truy cập http://localhost/BKMusic trên trình duyệt

📷 Giao diện (demo)
Bạn có thể chèn ảnh hoặc GIF giới thiệu nếu có:

scss
Sao chép
Chỉnh sửa
![Trang chủ](assets/screenshots/homepage.png)
🤝 Đóng góp
Mọi đóng góp đều được hoan nghênh:

Fork repo

Tạo nhánh mới: git checkout -b feature/tinh-nang-moi

Commit: git commit -m "Thêm tính năng xyz"

Push và tạo Pull Request

