1. Giới thiệu đề tài

Đề tài xây dựng một ứng dụng web quản lý nhà cung cấp và sản phẩm nhằm hỗ trợ công tác quản lý thông tin trong doanh nghiệp.
Ứng dụng cho phép:

Quản lý danh sách nhà cung cấp (thêm, sửa, xóa, tìm kiếm).

Quản lý danh sách sản phẩm (thêm, sửa, xóa, gắn với nhà cung cấp).

Lưu trữ dữ liệu tập trung trong MongoDB, giúp dễ dàng mở rộng và khai thác.

2. Mục tiêu

Vận dụng kiến thức về Node.js, Express, MongoDB để phát triển ứng dụng thực tế.

Rèn luyện kỹ năng xây dựng ứng dụng web theo mô hình MVC.

Thực hành kết nối cơ sở dữ liệu NoSQL và triển khai CRUD.

Hoàn thiện kỹ năng quản lý project với Git/GitHub.

3. Công nghệ sử dụng

Ngôn ngữ lập trình: JavaScript (Node.js)

Framework backend: Express.js

Cơ sở dữ liệu: MongoDB (Mongoose ODM)

Template engine: EJS

CSS framework: Bootstrap 5

Quản lý phiên bản: Git, GitHub

4. Kiến trúc hệ thống

Ứng dụng được thiết kế theo mô hình MVC (Model – View – Controller):

Model: định nghĩa schema (Supplier, Product) bằng Mongoose.

View: sử dụng EJS kết hợp Bootstrap để hiển thị.

Controller: xử lý logic CRUD và tương tác với database.

5. Các chức năng chính
5.1. Nhà cung cấp (Supplier)

Thêm mới nhà cung cấp.

Chỉnh sửa thông tin nhà cung cấp.

Xóa nhà cung cấp.

Xem danh sách nhà cung cấp.

5.2. Sản phẩm (Product)

Thêm mới sản phẩm.

Chỉnh sửa thông tin sản phẩm.

Xóa sản phẩm.

Liên kết sản phẩm với nhà cung cấp.
