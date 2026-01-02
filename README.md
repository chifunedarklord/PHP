# HƯỚNG DẪN SỬ DỤNG FILE TRÊN GITHUB

## 1. Thông tin sinh viên
- **Họ và tên:** Bùi Đức Đoàn  
- **Mã sinh viên:** 20230381  
- **Trường:** Đại học Công nghệ Đông Á  

---

## 2. Giới thiệu
Repository này dùng để lưu trữ và chia sẻ các file/bài tập đã được upload lên GitHub.  
Người dùng có thể xem mã nguồn trực tiếp trên GitHub hoặc tải về máy để chạy và chỉnh sửa.
---

## 3. Cách tải file / folder về máy

### 🔹 Cách 1: Tải toàn bộ project
1. Nhấn **Code**
2. Chọn **Download ZIP**
3. Giải nén và sử dụng

### 🔹 Cách 2: Tải 1 folder cụ thể
- Copy link folder  
- Dán vào trang:  
  https://download-directory.github.io/

---

## 4. Cách chạy file sau khi tải về
(Tùy theo loại bài tập)

- **HTML/PHP:**  
  Mở bằng VS Code, chạy bằng trình duyệt hoặc localhost (XAMPP)

- **C# WinForms:**  
  Mở file `.sln` bằng Visual Studio → Run

- **Java/Android:**  
  Mở bằng Android Studio hoặc IDE phù hợp

---
## HƯỚNG DẪN CHẠY DỰ ÁN BẰNG XAMPP

### 1. Giải nén folder dự án
- Tải file `.zip` của dự án từ GitHub
- Giải nén file `.zip` ra thư mục mong muốn

---

### 2. Đưa dự án vào thư mục `htdocs`
- Copy toàn bộ **folder dự án** vừa giải nén
- Dán vào thư mục `htdocs` của XAMPP

**Đường dẫn mặc định:**
- **Windows:**  
  `C:\xampp\htdocs\`
- **MacOS:**  
  `/Applications/XAMPP/htdocs/`

📌 Ví dụ: 
`C:\xampp\htdocs\my-project`

---

### 3. Khởi động XAMPP
1. Mở **XAMPP Control Panel**
2. Nhấn **Start**:
   - Apache
   - MySQL (nếu dự án có sử dụng cơ sở dữ liệu)

---

### 4. Truy cập dự án trên trình duyệt
1. Mở trình duyệt web (Chrome, Edge, Firefox, ...)
2. Nhập địa chỉ:`http://localhost/tên-folder-dự-án`
   
📌 Ví dụ:`http://localhost/my-project`

---

### 5. Ghi chú
- Đảm bảo **Apache đang chạy** trước khi truy cập
- Nếu có lỗi, kiểm tra lại:
  - Tên folder dự án
  - Cổng Apache (mặc định là 80)
  - File `index.php` hoặc `index.html` trong thư mục dự án
