<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
    🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>
<h2 align="center">
   ỨNG DỤNG CHUYỂN ĐỔI SỐ TRONG BỆNH VIỆN
</h2>
<div align="center">
    <p align="center">
        <img alt="AIoTLab Logo" width="170" src="https://github.com/user-attachments/assets/711a2cd8-7eb4-4dae-9d90-12c0a0a208a2" />
        <img alt="AIoTLab Logo" width="180" src="https://github.com/user-attachments/assets/dc2ef2b8-9a70-4cfa-9b4b-f6c2f25f1660" />
        <img alt="DaiNam University Logo" width="200" src="https://github.com/user-attachments/assets/77fe0fd1-2e55-4032-be3c-b1a705a1b574" />
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)
</div>

## 📖 1. Giới thiệu hệ thống 
Ứng dụng Chuyển đổi số trong bệnh viện được xây dựng nhằm hỗ trợ công tác quản lý, tra cứu và xử lý thông tin y tế một cách nhanh chóng, chính xác và hiệu quả thông qua mô hình Client – Server. Hệ thống giúp số hóa quy trình làm việc giữa các khoa phòng, bác sĩ, y tá và bệnh nhân, góp phần nâng cao chất lượng dịch vụ khám chữa bệnh và giảm thiểu sai sót trong quản lý hồ sơ y tế.

🎯 Các chức năng chính:<br>
> ● Quản lý hồ sơ bệnh nhân: Lưu trữ, tra cứu và cập nhật thông tin bệnh nhân một cách tập trung và bảo mật.<br>
> ● Quản lý lịch khám và điều trị: Hỗ trợ đặt lịch khám, phân bổ bác sĩ, theo dõi tiến trình điều trị.<br>
> ● Quản lý thuốc và vật tư y tế: Theo dõi tồn kho, nhập xuất thuốc và vật tư theo từng khoa.<br>
> ● Hỗ trợ thống kê và báo cáo: Cung cấp báo cáo nhanh về tình hình bệnh nhân, doanh thu, và hoạt động của bệnh viện.<br>
> ● Tích hợp thông tin liên khoa: Cho phép chia sẻ và truy cập thông tin bệnh án giữa các khoa để phối hợp điều trị hiệu quả.<br>

        

## 🔧 2. Công nghệ sử dụng: [![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)

- **PHP** – Ngôn ngữ lập trình chính, xử lý logic phía server và kết nối với cơ sở dữ liệu.  
- **MySQL** – Hệ quản trị cơ sở dữ liệu, lưu trữ thông tin bệnh nhân, lịch khám, thuốc và các dữ liệu y tế khác.
- **HTML/CSS/JavaScript** – Xây dựng giao diện web, tạo trải nghiệm người dùng thân thiện và tương tác động.  
- **Apache /Xampp** – Web server để chạy ứng dụng PHP.  
---
## 🖼️ 3.  Hình ảnh các chức năng chính

### 🔹 Giao diện màn hình chính 
[[![alt text](image.png)](https://github.com/NguyenKhanh04/CDS-Ung_Dung_CDS_Trong_Quan_Li_Benh_Vien/raw/main/image-1.png)](https://github.com/NguyenKhanh04/CDS-Ung_Dung_CDS_Trong_Quan_Li_Benh_Vien/raw/main/image-1.png)

### 🔹 Tính năng chatbot nổi bật và chuyển đổi số
[![alt text](image-1.png)](https://github.com/NguyenKhanh04/CDS-Ung_Dung_CDS_Trong_Quan_Li_Benh_Vien/raw/main/image-1.png)



## 🚀 4.  Các bước cài đặt

### Bước 1: Chuẩn bị môi trường
- Cài đặt môi trường chạy PHP: **XAMPP**.
 
- Bật các dịch vụ: **Apache (Web Server)** và **MySQL (Database Server)**. 

- Clone project từ GitHub về máy:  
  ```bash
  https://github.com/NguyenKhanh04/CDS-Ung_Dung_CDS_Trong_Quan_Li_Benh_Vien.git

### Bước 2: Cấu hình cơ sở dữ liệu
- Truy cập phpMyAdmin:
  👉 http://localhost/phpmyadmin

- Tạo database, ví dụ: "quanlybenhvien"

- Import file SQL có sẵn trong project (/database/quanlybenhvien.sql).

- Kiểm tra lại kết nối trong file cấu hình PHP:
  (config.php hoặc db_connect.php)

### Bước 3: Khởi động ứng dụng
- Copy toàn bộ source code vào thư mục:
📁 htdocs/benhvien (dùng XAMPP)

- Mở trình duyệt và truy cập:
👉 http://localhost/quanlybenhvien

- Hệ thống sẽ điều hướng đến trang đăng nhập hoặc dashboard.
### Bước 4: Sử dụng hệ thống 🎉
- **Quản lý hồ sơ bệnh nhân**: thêm – sửa – xem – tìm kiếm.

- **Quản lý lịch khám**: đặt lịch, xem lịch theo bác sĩ/khoa.

- **Quản lý thuốc & vật tư**: theo dõi tồn kho, nhập – xuất – báo cáo.

- **Quản lý nhân sự bệnh viện**: bác sĩ, y tá, hành chính.

- **Thống kê & báo cáo**: số lượng bệnh nhân, doanh thu, lượt khám,...


## 📞 5. Liên hệ <br>
 📌 © 2025 **Nhóm 20: Nguyễn Ngọc Khánh & Bùi Văn Tiến Lớp: CNTT 16-03**,<br> Faculty of Information Technology – DaiNam University. All rights reserved.<br>
