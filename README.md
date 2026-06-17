# Selenium Automation Test

## Website

https://www.saucedemo.com/

## Công cụ

* Java 21
* Selenium 4
* Maven
* TestNG
* ChromeDriver

## Test Case 1 - Login

Mục tiêu:

Kiểm tra chức năng đăng nhập.

Các bước:

1. Mở website.
2. Nhập username: `standard_user`.
3. Nhập password: `secret_sauce`.
4. Nhấn Login.

Kết quả mong đợi:

Đăng nhập thành công và chuyển đến trang Products.

---

## Test Case 2 - Add Product to Cart

Mục tiêu:

Kiểm tra chức năng thêm sản phẩm vào giỏ hàng.

Các bước:

1. Đăng nhập.
2. Chọn sản phẩm **Sauce Labs Backpack**.
3. Nhấn **Add to cart**.

Kết quả mong đợi:

Biểu tượng giỏ hàng hiển thị số lượng **1**.

---

## Test Case 3 - Logout

Mục tiêu:

Kiểm tra chức năng đăng xuất.

Các bước:

1. Mở menu.
2. Chọn **Logout**.

Kết quả mong đợi:

Hệ thống quay về trang đăng nhập.

---

## Kết luận

Đã xây dựng 03 test case kiểm thử tự động bằng Selenium gồm: đăng nhập, thêm sản phẩm vào giỏ hàng và đăng xuất. Tất cả các test đều thực thi thành công.
