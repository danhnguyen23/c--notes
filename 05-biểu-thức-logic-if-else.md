**Kiểu dữ liệu `bool`**

Ngoài 4 kiểu dữ liệu đã học là `int`, `float`, `char` và `string`; còn một loại nữa là `bool` (viết tắt của Boolean).

Kiểu `bool` chỉ có hai giá trị duy nhất là `true` (đúng) và `false` (sai).

---

**Các toán tử so sánh**

Trong C++, chúng ta có những toán tử dùng để so sánh sau đây:

```
== - so sánh bằng
!= - so sánh khác
>  - so sánh lớn
<  - so sánh bé
>= - so sánh lớn hơn hoặc bằng
<= - so sánh bé hơn hoặc bằng
```

Nếu muốn so sánh 2 giá trị A và B, trong C++ ta sử dụng cú pháp như sau: **A TOÁN_TỬ_SO_SÁNH B** - đây được gọi là một
biểu thức so sánh. Và kết quả trả về của một biểu thức so sánh là một giá trị kiểu `bool` (đúng hoặc sai / true hoặc false).

Ví dụ:

```
1 == 1: kết quả là true
3 == 4: kết quả là false
3 > 2 : kết quả là true
1 != 1: kết quả là false
```

---

**Câu lệnh điều kiện if/else**

Câu lệnh điều kiện if/else giúp ta điều hướng được chương trình C++ thực hiện những phần câu lệnh khác nhau tùy thuộc vào
các điều kiện nào đó.

Có 3 cú pháp của câu lệnh điều kiện if/else như sau:

```C++
// Cú pháp 1
if (BIỂU_THỨC_ĐIỀU_KIỆN) {
    // Các câu lệnh được thực thi
    // khi BIỂU_THỨC_ĐIỀU_KIỆN là đúng
}

// Cú pháp 2
if (BIỂU_THỨC_ĐIỀU_KIỆN) {
    // Các câu lệnh được thực thi
    // khi BIỂU_THỨC_ĐIỀU_KIỆN là đúng
} else {
    // Các câu lệnh được thực thi
    // khi BIỂU_THỨC_ĐIỀU_KIỆN là sai
}
```
