# lab04
Mảng -  Chuỗi - OOP - Thực hành parse dữ liệu
Bài 1: Chuỗi → Danh sách tên (GET)
File:
- ex1_names.php
Link chạy:
http://localhost/lab04/ex1_names.php?names=An,Binh, Chi, ,Dung

Chức năng:
- Tách chuỗi bằng dấu phẩy
- Trim, loại phần tử rỗng
- Hiển thị danh sách tên và số lượng
Bài 2: Mảng điểm: Thống kê + Sắp xếp
File:
- ex2_scores.php
Link chạy:
http://localhost/lab04/ex2_scores.php

Chức năng:
- Tính điểm trung bình
- Đếm điểm >= 8.0
- Tìm max, min
- Sắp xếp tăng / giảm
Bài 3: Giỏ hàng (Mảng nhiều chiều)
File:
- ex3_cart.php
Link chạy:
http://localhost/lab04/ex3_cart.php

Chức năng:
- Tính amount = price * qty
- Hiển thị bảng sản phẩm
- Tính tổng tiền
- Sort theo price giảm dần
Bài 4: OOP Student + Render + Thống kê
File:
- Student.php
- ex4_students.php
Link chạy:
http://localhost/lab04/ex4_students.php

Chức năng:
- Class Student (id, name, gpa)
- Xếp loại: Giỏi / Khá / Trung bình
- Tính GPA trung bình lớp
- Thống kê theo rank
Bài 5: Student Manager (POST)
File:
- Student.php
- ex5_student_manager.php
Link chạy:
http://localhost/lab04/ex5_student_manager.php
Dữ liệu mẫu nhập vào textarea:
SV001-An-3.2;
SV002-Binh-2.6;
SV003-Chi-3.5;
SV004-Dung-3.8

Chức năng:
- Parse chuỗi → Student[]
- Bỏ record sai định dạng
- Lọc GPA theo threshold
- Sort GPA giảm dần
- Thống kê: avg, max, min, rank
Bài 6A: Quản lý thư viện mini (Library Manager)
File:
- Book.php
- ex6_library_manager.php
Link chạy:
http://localhost/lab04/ex6_library_manager.php
Dữ liệu mẫu nhập vào textarea:
B001-Intro to PHP-2;
B002-Web Programming-5;
B003-Database Basics-1

Chức năng:
- Parse chuỗi → Book[]
- Tìm theo Title (không phân biệt hoa thường)
- Sort Qty giảm dần
- Thống kê thư viện
Bài 6B: Mini Sales Manager
File:
- Product.php
- ex6_sales_manager.php
Link chạy:
http://localhost/lab04/ex6_sales_manager.php
Dữ liệu mẫu nhập vào textarea:
P001-Rice Cooker-120-2;
P002-Kettle-45-1;
P003-Blender-80-3

Chức năng:
- Parse chuỗi → Product[]
- Lọc theo Min Price
- Sort Amount giảm dần
- Tính tổng tiền, avg price
- Đánh dấu Invalid qty

GHI CHÚ:
- Khi in dữ liệu ra HTML đều sử dụng htmlspecialchars()
- Record sai định dạng sẽ bị bỏ qua, không làm crash chương trình
- Chạy trên localhost với XAMPP
