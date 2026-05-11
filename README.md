# TRƯỜNG ĐẠI HỌC BÁCH KHOA - ĐẠI HỌC ĐÀ NẴNG
## KHOA ĐIỆN TỬ VIỄN THÔNG

---

# 🚀 ĐỒ ÁN: HỆ THỐNG QUẢN LÝ TOUR DU LỊCH (PBL1)

![Project Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)

## 👨‍💻 THÔNG TIN SINH VIÊN & GIẢNG VIÊN
*   **Sinh viên thực hiện:** [Cao Tiến Dũng](https://github.com/caotiendung111)
*   **Giảng viên hướng dẫn:** **TS. Đào Duy Tuấn**
*   **Học phần:** Dự án liên môn 1 (PBL1) - Lập trình C/C++
*   **Cơ quan:** TRƯỜNG ĐẠI HỌC BÁCH KHOA - ĐẠI HỌC ĐÀ NẴNG

---

## 📝 GIỚI THIỆU DỰ ÁN
Dự án được xây dựng nhằm giải quyết bài toán quản lý tour du lịch thực tế, cho phép doanh nghiệp lữ hành số hóa quy trình quản lý khách hàng và tour du lịch. Hệ thống sử dụng ngôn ngữ C++ thuần túy, kết hợp với các kỹ thuật quản lý bộ nhớ và cấu trúc dữ liệu tối ưu để đảm bảo hiệu suất cao trên môi trường Console.

## 🌟 TÍNH NĂNG CHI TIẾT (19+ CHỨC NĂNG)

### 🛡 Module Quản Trị Viên (Admin Control Panel)
Hệ thống cung cấp một bảng điều khiển tập trung giúp Admin có toàn quyền kiểm soát dữ liệu:
*   **Quản lý Thực thể:** Thêm, xóa và sửa đổi thông tin Khách hàng & Tour du lịch với độ chính xác tuyệt đối.
*   **Thuật toán Sắp xếp:** 
    *   Sắp xếp khách hàng theo độ tuổi (Năm sinh).
    *   Sắp xếp Tour theo giá tiền để tối ưu hóa chiến dịch marketing.
    *   Sắp xếp theo thời gian khởi hành.
*   **Công cụ Tìm kiếm:** Tìm kiếm đa tiêu chí (Mã tour, Tên tour, CMND khách hàng, Khoảng giá).
*   **Phân tích & Thống kê:** 
    *   Thống kê doanh thu thực tế dựa trên số vé đã bán.
    *   Phân tích Tour "Hot" nhất trong tháng.
    *   Truy xuất lịch sử giao dịch (File `billQuanLi.txt`).

### 🛍 Module Khách Hàng (Customer Experience)
*   **Quy trình Booking:** Đăng ký tài khoản -> Đăng nhập -> Chọn Tour -> Áp dụng mã giảm giá -> Nhận hóa đơn.
*   **Cơ chế Voucher:** Tự động tính toán chiết khấu (10% - 20%) khi nhập các mã khuyến mãi hợp lệ.
*   **Quản lý Sức chứa:** Hệ thống tự động khóa Tour khi số chỗ đã đầy (Full capacity handling).
*   **Hóa đơn điện tử:** Xuất hóa đơn chi tiết bao gồm thời gian thực (Giờ/Phút/Giây) lưu trực tiếp vào bộ nhớ máy tính.

## 🏗 CẤU TRÚC MÃ NGUỒN
*   `MainDulich2HDH2.cpp`: Chứa logic điều hướng, xử lý menu và các thuật toán cốt lõi.
*   `Do_Hoa.h`: Thư viện xử lý đồ họa Console (Tọa độ, Màu sắc, Khung hình).
*   `ThongTinTour.txt`: Cơ sở dữ liệu lưu trữ thông tin các chuyến đi.
*   `Nguoi.txt`: Cơ sở dữ liệu lưu trữ hồ sơ khách hàng.
*   `billKhachHang.txt`: Lưu trữ hóa đơn lần cuối cho người dùng.

## 🛠 HƯỚNG DẪN CÀI ĐẶT & SỬ DỤNG

### Bước 1: Chuẩn bị môi trường
Đảm bảo máy tính đã cài đặt trình biên dịch **MinGW** hoặc **TDM-GCC**.

### Bước 2: Biên dịch dự án
```powershell
g++ MainDulich2HDH2.cpp -o Dulich.exe
```

### Bước 3: Khởi động hệ thống
```powershell
.\Dulich.exe
```

## 📈 ĐỊNH HƯỚNG PHÁT TRIỂN
1.  Nâng cấp giao diện lên GUI (Graphics User Interface) sử dụng Qt hoặc MFC.
2.  Kết nối cơ sở dữ liệu SQL Server/MySQL thay vì file text.
3.  Tích hợp API thanh toán trực tuyến và bản đồ Tour.

---
**TRƯỜNG ĐẠI HỌC BÁCH KHOA - ĐẠI HỌC ĐÀ NẴNG**  
*Chất lượng - Sáng tạo - Chuyên nghiệp*
