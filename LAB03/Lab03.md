# LAB03 – Hoàn thiện Backend cho ứng dụng minh họa

---

## Thông tin sinh viên

- Họ tên: Đinh Nguyễn Đức Tâm
- MSSV: 23521384
- Môn học: IE213.Q21 – Kỹ thuật phát triển hệ thống Web
- Lớp: IE213.Q21.1

---

## Mục tiêu

- Xây dựng chức năng Review cho ứng dụng
- Hoàn thiện backend với mô hình DAO – Controller – Route
- Thực hiện các thao tác CRUD cho review
- Xây dựng các API nâng cao cho movies

---

## Công cụ sử dụng

- NodeJS
- ExpressJS
- MongoDB Atlas
- MongoDB Compass
- VS Code
- Insomnia

---

## Cấu trúc thư mục bài thực hành 2

```text
LAB03
├── movie-reviews/
│   └── backend/
│       ├── api/
│       │   ├── movies.controller.js
│       │   ├── movies.route.js
│       │   └── reviews.controller.js
│       ├── dao/
│       │   ├── moviesDAO.js
│       │   └── reviewsDAO.js
│       ├── index.js
│       ├── server.js
│       └── package.json
├── screenshots/
└── Lab03.md
```

---

## Thực hiện

### Bài 1: Thiết lập định tuyến cho các thao tác với review (Post/Update/Delete)

**Kết quả**

[movies.route.js](./movie-reviews/backend/api/movies.route.js)

![1](./Results/1.png)

### Bài 2: Thiết lập Controller cho review.

Tạo tệp tin reviews.controller.js để quản lý các yêu cầu có liên quan đến review từ người dùng gửi lên từ máy khách bao gồm các function:<br>

**Kết quả**

[reviews.controller.js](./movie-reviews/backend/api/reviews.controller.js)

### Bài 2.2:Trong tệp tin vừa tạo ở bài 2.1 sẽ chứa dòng lệnh import nội dung từ tệp tin reviewsDAO.js để gọi tới các hàm tương tác dữ liệu.

![2.2](./Results/2.2.png)

### Bài 2.3:Tạo phương thức có tên apiPostReview() để quản lý các yêu cầu được gửi từ máy khách

![2.3](./Results/2.3.png)

### Bài 2.4:Tạo phương thức có tên apiUpdateReview() để quản lý các yêu cầu được gửi từ máy khách

![2.4](./Results/2.4.png)

### Bài 2.5:Tạo phương thức có tên apiDeleteReview() để quản lý các yêu cầu được gửi từ máy khách

![2.5](./Results/2.5.png)

### Bài 3: Thiết lập DAO cho reviews.

DAO dùng để thao tác với database MongoDB bao gồm các function:<br>

**Kết quả**

[reviewsDAO.js](./movie-reviews/backend/dao/reviewsDAO.js)

#### Bài 3.2 Tạo phương thức có tên injectDB() giúp kết nối tới collection tương ứng trên db.

![3.2](./Results/3.2.png)

#### Bài 3.3 Tạo phương thức addReview() để thêm review vào db

![3.3](./Results/3.3.png)

#### Bài 3.4 Tạo phương thức updateReview() để sửa review trên db

![3.4](./Results/3.4.png)

#### Bài 3.5 Tạo phương thức deleteReview() để thêm review vào db

![3.5](./Results/3.5.png)

#### Bài 3.6 Thử nghiệm các API bằng phần mềm hỗ trợ Insomnia

**Kết quả**

Thêm dữ liệu

![3.6.1](./Results/3.6.1.png)

Sửa dữ liệu

![3.6.2](./Results/3.6.2.png)

Xóa dữ liệu

![3.6.3](./Results/3.6.3.png)

### Bài 4: Hoàn thành back-end cho ứng dụng minh họa.

#### Bài 4.1 Thêm 2 định tuyến

**Kết quả**

[movies.route.js](./movie-reviews/backend/api/movies.route.js)

![4.1](./Results/4.1.png)

#### Bài 4.2 Thêm 2 phương thức apiGetMovieById() và apiGetRatings() trong movie controller.

**Kết quả**

[movies.controller.js](./movie-reviews/backend/api/reviews.controller.js)

![4.2](./Results/4.2.png)

#### Bài 4.3 Thêm 2 phương thức DAO getRatings() và getMovieById() trong dao movie.

**Kết quả**

[moviesDAO.js](./movie-reviews/backend/dao/moviesDAO.js)

![4.3](./Results/4.3.png)

#### Bài 4.4 Thử nghiệm các API bằng phần mềm hỗ trợ Insomnia

**Kết quả**

Lấy theo ratings

![4.4.1](./Results/4.4.1.png)

Lấy theo id

![4.4.2](./Results/4.4.2.png)
