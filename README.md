# IE213 – KỸ THUẬT PHÁT TRIỂN HỆ THỐNG WEB

---

# 1. Thông tin sinh viên

- Họ tên: Đinh Nguyễn Đức Tâm
- MSSV: 23521384
- Môn học: IE213.Q21 – Kỹ thuật phát triển hệ thống Web
- Lớp: IE213.Q21.1

---

# 2. Giới thiệu

Repository này lưu trữ toàn bộ các bài thực hành của môn **IE213 – Kỹ thuật phát triển hệ thống Web**.

Mỗi bài lab được lưu trong một thư mục riêng để giảng viên có thể theo dõi tiến trình phát triển bài làm thực hành trong suốt học kỳ.

---

# 3. Cấu trúc

```id="3rj1mj"
23521384-DinhNguyenDucTam-IE213.Q21
│
├── README.md
├── LAB01
├── LAB02
├── LAB03
├── LAB04
├── LAB05
└── LAB06
```

---

# 4. Danh sách các Lab

## Lab01 – MongoDB CRUD Operation

Nội dung chính:

- Thiết lập MongoDB Atlas
- Kết nối MongoDB Compass
- Tạo database và collection
- Thực hiện CRUD bằng mongosh
- Thực hiện truy vấn dữ liệu và aggregation

Thư mục:

```id="h9mn6n"
LAB01/
```

## Lab02 - Thiết lập Backend với NodeJS và ExpressJS

Nội dung chính:

- Thiết lập môi trường NodeJS
- Xây dựng server với ExpressJS
- Kết nối MongoDB Atlas
- Tổ chức project theo mô hình DAO – Controller – Route
- Xây dựng API /api/v1/movies

Thư mục:

```id="h9mn6n"
LAB02/
```

## Lab03

## Lab04

## Lab05

## Lab06

---

# 5. Cách chạy chương trình

Đối với Lab01:

1. Đăng nhập MongoDB Atlas
2. Kết nối MongoDB Compass với cluster
3. Mở Mongo Shell (mongosh)
4. Chạy các lệnh MongoDB được ghi trong file Lab01

Ví dụ:

```javascript id="k9eeyv"
use 23521384-IE213
```

Sau đó thực hiện các lệnh CRUD theo yêu cầu của bài thực hành.

Đối với Lab02:

1. Di chuyển vào thư mục backend cd lab02/movie-reviews/backend
2. Cài đặt dependency npm install
3. Chạy server npm start
4. Truy cập API http://localhost:3000/api/v1/movies

---

# 6. Kết quả thực hiện

Đã thực hiện thành công các yêu cầu của Lab01:

- Tạo database MongoDB
- Thêm document vào collection
- Tạo unique index
- Thực hiện các truy vấn find()
- Thực hiện updateMany()
- Thực hiện aggregation

Kết quả được minh họa bằng hình ảnh trong thư mục:

```id="hweay3"
LAB01/Results
```

Đã thực hiện thành công các yêu cầu của Lab02:

- Thiết lập môi trường NodeJS
- Cài đặt ExpressJS và MongoDB
- Xây dựng server backend
- Thiết lập API /api/v1/movies
- Kết nối MongoDB Atlas

Kết quả được minh họa bằng hình ảnh trong thư mục:

```id="hweay3"
LAB02/Results
```

---

# 7. Hình ảnh minh họa

Các hình ảnh minh chứng kết quả thực hiện được lưu trong thư mục Results tương ứng với từng bài thực hành.

Cấu trúc thư mục:

```id="hweay3"
LAB01/Results
LAB02/Results
LAB03/Results
LAB04/Results
LAB05/Results
LAB06/Results
```

---
