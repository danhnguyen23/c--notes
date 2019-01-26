Biến số (variables) là nơi để lưu giá trị.

---

**Cách sử dụng biến**:

Ta đã học 4 kiểu dữ liệu cơ bản của C++ là:
- Số nguyên: **int**.
- Số thực/số thập phân: **float**.
- Kí tự: **char**.
- Chuỗi: **string**.

Tương ứng, ta sẽ có 4 kiểu biến để lưu 4 kiểu dữ liệu này.

Để khai báo một biến: `KIỂU_DỮ_LIỆU TÊN_BIẾN`. Ví dụ:

```C++
int x;  // Có nghĩa là: khai báo một biến x có kiểu int (nguyên) để lưu số nguyên.
float y;
char c;
string ten;
```

Khi khai báo một biến, thì biến này chưa được gán giá trị nào cả, lúc này C++ sẽ tự động gán
cho chúng một giá trị ngẫu nhiên nào đó (gọi là giá trị rác). Như vậy, chúng ta chưa thể dùng
ngay biến vừa mới khai báo được mà trước hết phải gán giá trị cho nó.

Để gán giá trị cho biến: `TÊN_BIẾN = GIÁ_TRỊ`. Ví dụ:

```C++
x = 1
y = 2.3
c = 'D'  // Lưu ý, vì biến c thuộc kiểu char, nên ta không thể gán một chuỗi cho nó như là c = "D"
ten = "Nguyen Thanh Danh"
```

**Lưu ý**:
- Ta không thể sử dụng biến mà không khai báo nó trước.
- Trước khi sử dụng biến, ta phải gán cho nó một giá trị ban đầu nào đó.
- Có thể vừa khai báo, vừa gán giá trị ban đầu cho một biến như sau:
  ```C++
  int x = 1;
  
  // Câu lệnh trên tương đương với:
  int x;
  x = 1;
  ```
  
---

**Bài tập**:

3.1. Hãy lưu tên của bạn vào một biến và in ra biến đó.
