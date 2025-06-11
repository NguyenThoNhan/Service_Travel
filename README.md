## Firstflight Travels

A travel website project created using HTML, CSS and JavaScript.

➡️ [Live Demo](https://nguyenthonhan.github.io/Service_Travel/client)

📋 Phân tích Yêu cầu
a. 🎯 Đặt vấn đề bài toán
Hệ thống quản lý tour du lịch giúp người dùng tìm kiếm, đăng ký và thanh toán các tour du lịch một cách thuận tiện.
Hệ thống tích hợp:

Chatbot AI để hỗ trợ tư vấn và trả lời câu hỏi.

Đăng nhập bằng nhận diện khuôn mặt nhằm nâng cao bảo mật và trải nghiệm người dùng.

b. 👤 Tác nhân, người dùng
User (Khách hàng): người sử dụng hệ thống để tìm kiếm và đặt tour.

Admin (Quản trị viên): người quản lý nội dung, người dùng, chatbot và giao dịch.

c. ⚙️ Chức năng theo tác nhân
👉 User:
Đăng nhập bằng khuôn mặt

Tìm kiếm tour

Xem thông tin chi tiết tour

Đăng ký tour

Thanh toán trực tuyến

Hỏi đáp, nhận tư vấn từ chatbot AI

👉 Admin:
Quản lý danh sách tour (thêm/sửa/xoá)

Quản lý người dùng

Quản lý giao dịch, thống kê

Cập nhật và quản lý chatbot AI

Hỗ trợ tư vấn người dùng qua hệ thống chatbot

🛠️ Đặc tả và Thiết kế
a. 📌 Use Case Diagram & Mô tả
Hệ thống gồm hai tác nhân chính: User và Admin.

User có thể tìm kiếm tour, xem thông tin, đăng ký, thanh toán và sử dụng chatbot hỗ trợ.

Admin có quyền quản lý chatbot, user, tour, giao dịch và tư vấn khách hàng.
Các use case chính được mô tả chi tiết trong sơ đồ Use Case.

b. 🔁 Flow (Activity Flow)
Sử dụng Activity Diagram để mô tả luồng xử lý đặt tour:

User tìm kiếm tour →

Xem thông tin chi tiết →

Đăng ký tour →

Tiến hành thanh toán →

Nhận xác nhận đặt tour.

c. 🧱 Thiết kế Hướng Đối Tượng
Hệ thống được thiết kế theo mô hình hướng đối tượng gồm các lớp chính:

User, Admin

Tour, Booking, Payment

Chatbot, SupportService
Mỗi lớp chịu trách nhiệm riêng biệt, đảm bảo nguyên lý SOLID và dễ mở rộng hệ thống.
