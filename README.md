❤️ Ứng dụng Todo MERN Stack 📋
Một ứng dụng danh sách công việc (todo) full-stack đơn giản nhưng mạnh mẽ được xây dựng bằng MERN stack. Tổ chức các nhiệm vụ của bạn một cách hiệu quả với giao diện người dùng sạch sẽ và có độ phản hồi cao.

🚀 Xem Demo Trực Tiếp 😍

🚀 Về Dự Án
Đây là một ứng dụng Todo full-stack cho phép người dùng tạo, đọc, cập nhật và xóa (CRUD) các tác vụ. Ứng dụng được xây dựng với MERN stack (MongoDB, Express.js, React.js, Node.js) nhằm cung cấp trải nghiệm người dùng mượt mà và nhanh chóng.

🛠️ Công Nghệ Sử Dụng
Client (Frontend):

React.js: Thư viện JavaScript để xây dựng giao diện người dùng.

HTML, CSS: Dùng để cấu trúc và tạo kiểu cho ứng dụng.

TailwindCSS: Một framework CSS ưu tiên tiện ích (utility-first) để phát triển giao diện nhanh chóng.

Server (Backend):

Node.js: Môi trường thực thi JavaScript.

Express.js: Framework ứng dụng web để xây dựng RESTful API.

Mongoose: Thư viện mô hình hóa đối tượng dữ liệu (ODM) cho MongoDB.

Cơ sở dữ liệu:

MongoDB: Cơ sở dữ liệu NoSQL để lưu trữ các ghi chú công việc.

🌱 Cấu Trúc Dự Án
Kho lưu trữ được tổ chức thành hai thư mục chính để tách biệt phần frontend và backend.

Bash
/MERN-Todo

├── client/                      # Ứng dụng Frontend React
│   ├── public/
│   ├── src/                     # Mã nguồn
│   │   └── App.jsx
│   ├── .env                     # Biến môi trường
│   ├── index.css                # Styles hệ thống
│   ├── index.html               # File HTML chính
│   └── index.jsx                # File khởi tạo React
│
└── server/                      # Ứng dụng Backend Node.js và Express.js
│   ├── controllers/             # Logic xử lý yêu cầu (request)
│   ├── models/                  # Cấu trúc dữ liệu Mongoose (Schemas)
│   ├── node_modules/
│   ├── routes/                  # Định nghĩa các đường dẫn API (Routes)
│   ├── .env                     # Biến môi trường
│   └── index.js                 # File khởi tạo Server
│
└── README.md                    # Tài liệu hướng dẫn dự án

🔥 Sao Chép Kho Lưu Trữ (Clone)
Bạn cần nhập các lệnh sau vào màn hình terminal (trong VS Code) để có thể chạy dự án này tại máy cục bộ.

Bash
git clone https://github.com/HuyGiaTran/Basic_ToDoList-with-MERN.git
Di chuyển vào thư mục dự án:

Bash
cd MERN-Todo
Cài đặt các thư viện phụ thuộc cho cả client và server:

# Cài đặt thư viện cho client
cd client
npm install

# Cài đặt thư viện cho server
cd ../server
npm install
Thiết lập biến môi trường:

.env - Các biến môi trường để dự án chạy trong môi trường phát triển (điền các giá trị thực tế cho các biến môi trường của bạn).

Chạy ứng dụng:

Tại thư mục server, khởi động backend server:

Bash
npm run start
Tại thư mục client, khởi động ứng dụng frontend:

Bash
npm run dev
Ứng dụng client sẽ chạy tại địa chỉ http://localhost:3000 và server sẽ lắng nghe tại http://localhost:5000.

Nếu bạn muốn Fork kho lưu trữ và chạy cục bộ, hãy làm theo hướng dẫn này: Fork và Clone kho lưu trữ Github

✏️ Đóng Góp
Đây là một kho lưu trữ mã nguồn mở và mọi đóng góp đều luôn được chào đón! Nếu bạn tìm thấy lỗi, vui lòng tạo một "issue" mới trong phần "Issues". Để đóng góp mã nguồn, hãy fork kho lưu trữ và gửi một "pull request". Sự đóng góp của bạn sẽ giúp dự án này trở thành tài nguyên quý giá cho cộng đồng!
