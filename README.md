# 📚 Library Management System

## 🚀 Tổng Quan Dự Án

Library Management System là một hệ thống quản lý thư viện được phát triển nhằm hỗ trợ việc quản lý sách, độc giả và các hoạt động mượn trả sách một cách hiệu quả. Hệ thống giúp tự động hóa các quy trình quản lý truyền thống, giảm thiểu sai sót trong quá trình nhập liệu, nâng cao khả năng tra cứu và theo dõi thông tin.

Dự án được xây dựng theo mô hình ứng dụng web với giao diện thân thiện, dễ sử dụng và có khả năng mở rộng trong tương lai. Hệ thống phù hợp với các thư viện trường học, thư viện doanh nghiệp và các tổ chức giáo dục.

---

## 🎯 Mục Tiêu

- Quản lý kho sách tập trung.
- Quản lý thông tin độc giả.
- Theo dõi việc mượn và trả sách.
- Hỗ trợ tìm kiếm sách nhanh chóng.
- Tự động thống kê và tạo báo cáo.
- Nâng cao hiệu quả quản lý thư viện.

---

## ✨ Chức Năng Chính

### 📖 Quản Lý Sách
- Thêm sách mới.
- Chỉnh sửa thông tin sách.
- Xóa sách khỏi hệ thống.
- Quản lý thể loại sách.
- Theo dõi số lượng sách tồn kho.

### 👤 Quản Lý Độc Giả
- Đăng ký độc giả mới.
- Cập nhật thông tin cá nhân.
- Tra cứu thông tin độc giả.
- Khóa hoặc mở khóa tài khoản.

### 🔄 Quản Lý Mượn Trả
- Lập phiếu mượn sách.
- Cập nhật trạng thái trả sách.
- Gia hạn thời gian mượn.
- Tính toán và cảnh báo sách quá hạn.

### 🔍 Tìm Kiếm Nâng Cao
- Tìm kiếm theo tên sách.
- Tìm kiếm theo tác giả.
- Tìm kiếm theo nhà xuất bản.
- Lọc theo thể loại sách.

### 📊 Báo Cáo - Thống Kê
- Tổng số sách hiện có.
- Tổng số lượt mượn sách.
- Sách được mượn nhiều nhất.
- Danh sách độc giả vi phạm hạn trả.
- Xuất báo cáo PDF hoặc Excel.

---

## 🛠️ Công Nghệ Sử Dụng

### Backend
- Java 17
- Spring Boot
- Spring Data JPA

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript

### Database
- MySQL 8.0

### Công Cụ Hỗ Trợ
- IntelliJ IDEA
- Visual Studio Code
- Git
- GitHub
- Postman

---

## 🏗️ Kiến Trúc Hệ Thống

```text
Client Browser
       │
       ▼
Frontend (HTML/CSS/JS)
       │
       ▼
Spring Boot REST API
       │
       ▼
MySQL Database
```

---

## 📂 Cấu Trúc Thư Mục

```text
LibraryManagementSystem
│
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── controller
│   │   │   ├── service
│   │   │   ├── repository
│   │   │   ├── model
│   │   │   └── config
│   │   │
│   │   ├── resources
│   │   │   ├── static
│   │   │   ├── templates
│   │   │   └── application.properties
│   │
│   └── test
│
├── database
│   └── library.sql
│
├── docs
│
└── README.md
```

---

## ⚙️ Cài Đặt

### Clone dự án

```bash
git clone https://github.com/your-username/library-management-system.git
```

### Di chuyển vào thư mục dự án

```bash
cd library-management-system
```

### Tạo cơ sở dữ liệu

```sql
CREATE DATABASE library_management;
```

### Chạy ứng dụng

```bash
mvn spring-boot:run
```

---

## 🔐 Phân Quyền Người Dùng

| Vai Trò | Quyền Hạn |
|----------|----------|
| Admin | Toàn quyền hệ thống |
| Librarian | Quản lý sách và mượn trả |
| Reader | Tra cứu thông tin và lịch sử mượn |

---

## ✅ Kiểm Thử

Các loại kiểm thử được thực hiện:

- Unit Testing
- Integration Testing
