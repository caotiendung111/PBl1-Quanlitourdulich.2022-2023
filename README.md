# TRƯỜNG ĐẠI HỌC BÁCH KHOA - ĐẠI HỌC ĐÀ NẴNG
## KHOA ĐIỆN TỬ VIỄN THÔNG

---

# 🚀 ĐỒ ÁN: HỆ THỐNG QUẢN LÝ TOUR DU LỊCH (PBL1)

![Project Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)
![Build](https://img.shields.io/badge/Build-v2.0-orange?style=for-the-badge)

## 👨‍💻 THÔNG TIN CHI TIẾT
*   **Sinh viên thực hiện:** [Cao Tiến Dũng](https://github.com/caotiendung111)
*   **Giảng viên hướng dẫn:** **TS. Đào Duy Tuấn**
*   **Học phần:** Dự án liên môn 1 (PBL1) - Lập trình C/C++
*   **Trường:** **TRƯỜNG ĐẠI HỌC BÁCH KHOA - ĐẠI HỌC ĐÀ NẴNG**

---

## 📝 GIỚI THIỆU TỔNG QUAN
Dự án **Hệ Thống Quản Lý Tour Du Lịch** là kết quả của quá trình nghiên cứu và ứng dụng ngôn ngữ lập trình C++ trong việc giải quyết các bài toán thực tế về quản lý dữ liệu. Hệ thống được thiết kế theo hướng đối tượng (OOP), tập trung vào tính linh hoạt, khả năng mở rộng và giao diện người dùng trực quan trên môi trường Console.

Dự án không chỉ dừng lại ở mức độ bài tập kỹ thuật mà còn tích hợp các quy trình nghiệp vụ thực tế như quản lý Voucher, kiểm soát sức chứa và xuất hóa đơn thời gian thực.

---

## 🌟 DANH SÁCH 19+ CHỨC NĂNG HỆ THỐNG

### 🛡 QUẢN TRỊ VIÊN (ADMIN)
Bảng điều khiển dành cho Admin được thiết kế bảo mật với tài khoản đăng nhập hệ thống, bao gồm các chức năng:
1.  **Thêm Khách hàng mới:** Nhập liệu hồ sơ khách hàng đầy đủ các trường thông tin.
2.  **Xóa Khách hàng:** Loại bỏ hồ sơ dựa trên số CMND.
3.  **Hiển thị danh sách Khách hàng:** Xuất dữ liệu dưới dạng bảng căn chỉnh đẹp mắt.
4.  **Hiển thị danh sách Tour:** Xem toàn bộ các gói du lịch hiện có.
5.  **Tìm kiếm Khách hàng:** Theo CMND hoặc Tên (không phân biệt hoa thường).
6.  **Tìm kiếm Tour:** Theo Mã Tour hoặc Tên Tour.
7.  **Sắp xếp Khách hàng theo Năm sinh:** Giúp phân loại độ tuổi khách hàng tiềm năng.
8.  **Sắp xếp Tour theo Giá tiền:** Từ cao xuống thấp để ưu tiên các Tour cao cấp.
9.  **Sắp xếp Tour theo Số ngày đi:** Giúp khách hàng chọn tour ngắn/dài ngày.
10. **Cập nhật thông tin Khách hàng:** Sửa đổi CMND, Họ tên, Quê quán, SDT, Mật khẩu...
11. **Cập nhật thông tin Tour:** Sửa đổi Tên, Giá, HDV, Khách sạn, Ngày khởi hành...
12. **Truy xuất Tour đắt nhất:** Tìm kiếm các gói dịch vụ Luxury.
13. **Truy xuất Tour rẻ nhất:** Tìm kiếm các gói du lịch tiết kiệm.
14. **Thêm Tour mới:** Mở rộng quy mô kinh doanh với các gói tour mới.
15. **Xóa Tour:** Loại bỏ các tour đã hết hạn hoặc ngừng kinh doanh.
16. **Lịch sử giao dịch:** Xem toàn bộ hóa đơn đã xuất trong file `billQuanLi.txt`.
17. **Thống kê doanh thu:** Phân tích tài chính dựa trên vé bán thực tế.
18. **Tìm kiếm theo khoảng giá:** Lọc dữ liệu phù hợp với ngân sách người dùng.
19. **Sao lưu dữ liệu:** Tự động ghi lại mọi thay đổi vào file hệ thống.

### 👥 KHÁCH HÀNG (CUSTOMER)
1.  **Đăng ký/Đăng nhập:** Quản lý tài khoản cá nhân bảo mật.
2.  **Tìm kiếm Tour:** Tìm các chuyến đi phù hợp.
3.  **Đặt Tour trực tuyến:** Hệ thống tự động trừ số chỗ (Slot) khi đặt thành công.
4.  **Áp dụng Voucher:** Tích hợp các mã giảm giá đặc biệt.
5.  **Nhận hóa đơn:** Hóa đơn được tạo tự động với đầy đủ thông tin cá nhân và chi tiết chuyến đi.

---

## 📐 KIẾN TRÚC DỮ LIỆU & LỚP (OOP)
Hệ thống được xây dựng trên nền tảng lập trình hướng đối tượng với cấu trúc phân cấp:
*   **Class `People`:** Lớp cơ sở chứa các thuộc tính chung của con người (Họ tên, CMND, Ngày sinh...).
*   **Class `Tourists` (Inheritance):** Kế thừa từ `People`, bổ sung các thuộc tính đặc thù của Tour du lịch (Mã tour, Giá tiền, HDV...).
*   **Tính Đóng gói (Encapsulation):** Sử dụng các hàm Getter/Setter để bảo vệ dữ liệu nội bộ.
*   **Tính Đa hình (Polymorphism):** Ghi đè phương thức hiển thị thông tin để phù hợp với từng đối tượng.

---

## 🛠 HƯỚNG DẪN SỬ DỤNG CHI TIẾT

### 1. Dành cho Admin
*   Đăng nhập với User: `admin` | Pass: `123`.
*   Chọn các phím chức năng từ 1-18 để quản lý dữ liệu.
*   Lưu ý: Mọi thay đổi sẽ được cập nhật trực tiếp vào file `.txt` để tránh mất dữ liệu khi tắt chương trình.

### 2. Dành cho Khách hàng
*   Sử dụng chức năng Đăng ký nếu chưa có tài khoản.
*   Khi đặt Tour, hãy nhập mã Voucher để nhận ưu đãi (Ví dụ: `DUT`, `BKDN`).
*   Xem hóa đơn tại thư mục dự án sau khi đặt Tour thành công.

---

## 📂 CẤU TRÚC THƯ MỤC
```text
DTVTPBL1_Freshman/
├── MainDulich2HDH2.cpp    # Mã nguồn chính (C++)
├── Do_Hoa.h               # Thư viện đồ họa Console
├── Dulich.exe             # File thực thi ứng dụng
├── Nguoi.txt              # Database Khách hàng
├── ThongTinTour.txt       # Database Tour
├── billQuanLi.txt         # Nhật ký hóa đơn hệ thống
└── README.md              # Tài liệu hướng dẫn
```

---

## 📜 CAM KẾT & BẢN QUYỀN
Dự án được thực hiện nghiêm túc dưới sự hướng dẫn của **TS. Đào Duy Tuấn**. Mọi hành vi sao chép cần được sự đồng ý của tác giả.

---
**TRƯỜNG ĐẠI HỌC BÁCH KHOA - ĐẠI HỌC ĐÀ NẴNG**  
*Khoa Điện tử Viễn thông - Niên khóa 2022-2023*
