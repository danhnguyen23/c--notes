Trong C++, biểu thức tính toán được viết không khác gì biểu thức được học ở trường.

Thứ tự thực hiện của các phép toán cũng là nhân chia trước, cộng trừ sau:

Ví dụ, trong C++, ta có thể viết:

```C++
4 * 3 - 2 * 1    // bằng 10

4 * 3 - 6 / 2    // bằng 9, phép chia trong C++ là /

4 * (3 - 2) * 1  // bằng 4
```

Tương tự, ta cũng có thể viết biểu thức số học cho số thực kiểu `float`:

```C++
1.0 * 2.0  // 2.0
```

Khi chúng ta viết một biểu thức có trộn lẫn giữa số `int` và `float`, số `int` sẽ chuyển thành `float`. Ví dụ:

```C++
2 * 1 = 2  // int * int = int

2 * 1.0 = 2.0  // int * float = float

2.0 - 1 = 1.0
```

Bởi vì biến được sử dụng để lưu giá trị, ta có thể sử dụng nó trong biểu thức một cách bình thường:

```C++
int x = 1;
int y = 2;

// Ta có thể viết:
x * y
x + y
2 * x - y
2 * x + 0.2
x / y
```

---

**Lưu ý về phép chia của số nguyên và thực**

Ôn lại về phép chia số nguyên, giả sử đặt phép tính A chia B và có kết quả như sau:

```
A | B
  |----
* | Q
R
```

Lúc này:
  - **Q gọi là phần nguyên** của phép chia A chia B.
  - **R gọi là phần dư** của phép chia A chia B.
  - Như vậy, có nghĩa rằng: `A = B * Q + R`.

Trong C++, khi chia 2 số nguyên cho nhau, ta sẽ được phần nguyên. Ví dụ:

```C++
9 / 2 = 4 (dư 1)
3 / 2 = 1 (dư 1)
10 / 5 = 2 (dư 0)
5 / 2 = 2 (dư 1)
```

Để lấy được giá trị thập phân chính xác của phép chia, ta thực hiện phép chia trên số thực:

```C++
9.0 / 2.0 = 4.5
9.0 / 2 = 4.5
9 / 2.0 = 4.5
```

Lưu ý:
- `3.0` có thể được viết là `3.`
- `0.5` có thể được viết là `.5`
