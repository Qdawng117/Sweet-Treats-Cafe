Tuyệt vời! Vì bạn đã tích hợp chat box bằng Tawk.to, mình sẽ cập nhật nội dung file `README.md` để phản ánh điều đó.

Dưới đây là file `README.md` hoàn chỉnh dành cho dự án **Sweet Treats Café**:

---

```markdown
# 🧁 Sweet Treats Café 

## 🎯 Mục Tiêu

Sweet Treats Café là nền tảng đặt bánh, cà phê và đồ ngọt trực tuyến, giúp khách hàng dễ dàng lựa chọn và đặt món ăn yêu thích từ các cửa hàng địa phương. Giao diện hiện đại, thân thiện, tối ưu cho cả máy tính và điện thoại.

## 🧩 Các Chức Năng Chính

### 1. Cho Người Dùng
- Xem danh sách sản phẩm: bánh, đồ uống, đồ ngọt với hình ảnh, mô tả, giá.
- Tìm kiếm món ăn theo tên hoặc loại.
- Thêm vào giỏ hàng, chọn số lượng, thêm ghi chú (ít đường, không đá...).
- Đặt hàng trực tuyến, nhập địa chỉ, theo dõi trạng thái đơn hàng.
- Đăng ký / đăng nhập tài khoản để lưu thông tin, lịch sử đơn hàng.

### 2. Cho Quản Trị Viên (Admin)
- Quản lý sản phẩm: thêm/sửa/xóa tên, mô tả, giá, hình ảnh.
- Quản lý đơn hàng: theo dõi, cập nhật trạng thái đơn hàng.
- Quản lý người dùng: phân quyền, khóa tài khoản.

## 🍩 Sản Phẩm Cung Cấp

### Bánh
- Bánh kem (gato, mousse), cupcakes, bánh quy, tart, bánh mì ngọt...

### Đồ Uống
- Cà phê (sữa đá, cappuccino, latte), trà sữa, sinh tố, cacao nóng...

### Đồ Ngọt
- Bánh flan, chè, macaron, kẹo, chocolate...

## 💻 Kiến Trúc Hệ Thống

### Frontend
- **Vue 3**: Framework xây dựng giao diện người dùng.
- **Tailwind CSS**: Thiết kế responsive, hiện đại.
- **Vue Router**: Quản lý các trang (route).
- **Pinia**: Quản lý trạng thái (giỏ hàng, người dùng).
- **Tawk.to Chat Widget**: Tích hợp hỗ trợ trực tuyến cho khách hàng.

### Backend
- **Node.js + Express**: Xử lý API và logic nghiệp vụ.
- **MongoDB**: Lưu trữ dữ liệu sản phẩm, đơn hàng, người dùng.
- **Mongoose**: ORM cho MongoDB.
- **JWT**: Xác thực người dùng.

## ⚙️ Cấu Trúc Thư Mục

### Frontend (`frontend/`)
```bash

frontend/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   ├── router/
│   ├── store/
│   ├── App.vue
│   └── main.js
├── index.html
├── tailwind.config.js
└── vite.config.js

```

### Backend (`backend/`)
```bash

backend/
├── controllers/
├── models/
├── routes/
├── middlewares/
├── config/
│   └── db.js
├── utils/
├── app.js
└── server.js

````

## 🧪 Dữ Liệu Mẫu MongoDB

### Collection: `products`
```json
{
  "name": "Bánh kem socola",
  "description": "Bánh mềm mịn, phủ socola đậm đà",
  "category": "cake",
  "price": 120000,
  "image": "/images/socola-cake.jpg"
}
````

## 📱 Quy Trình Hoạt Động

1. Người dùng đăng ký / đăng nhập.
2. Chọn món ăn, thêm vào giỏ hàng.
3. Xác nhận đơn, thanh toán và theo dõi trạng thái.
4. Admin nhận đơn, cập nhật tiến độ xử lý.
5. Người dùng nhận hàng và đánh giá.

## 🖥️ Giao Diện Mẫu

* Trang chủ: sản phẩm nổi bật.
* Giỏ hàng: chỉnh sửa số lượng, xóa món.
* Thanh toán: nhập địa chỉ, chọn hình thức giao hàng.
* Admin: quản lý sản phẩm, đơn hàng, người dùng.
* Chat Box: Tích hợp Tawk.to hỗ trợ người dùng theo thời gian thực.

## 🚀 Khởi Chạy Dự Án

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
npm install
npm run dev
```

> **Ghi chú:** Cần cài đặt MongoDB và cấu hình biến môi trường `.env`.

## 🌐 Liên Kết Tích Hợp

* [Tawk.to Dashboard](https://dashboard.tawk.to/)
* [MongoDB Atlas (hoặc local)](https://www.mongodb.com/atlas)

## ❤️ Cảm Ơn Đã Ghé Thăm Sweet Treats Café!

```

---

Bạn có muốn mình tạo file này và xuất ra tệp `.md` để tải xuống không?
```
