**Một chương trình C++ tối giản**

Mọi chương trình C++ đều có một hàm `main` (tiếng Việt nghĩa là "chính").

Hàm này được gọi là "ngõ vào" (tiếng Anh là Entry Point). Khi máy tính chạy chương trình C++, nó sẽ tìm hàm `main` này
và chạy nó trước.

Mọi hàm đều phải trả về một kết quả nào đó, giá trị này được trả về tại câu lệnh `return` (tiếng Việt nghĩa là "trả về").

Đối với hàm main:
- Giá trị trả về là 0: có nghĩa là chương trình không có lỗi.
- Giá trị trả về khác 0: nghĩa là chương trình có lỗi.

```C++
int main() {
  return 0;
}
```

---

**Một số kiểu dữ liệu cơ bản trong C++**:

- Số nguyên (integer): 0, 1 .. Có nhiều kiểu số nguyên trong C++:
  - `int`: số nguyên từ -2 tỉ đến 2 tỉ.
  - `long long int`: số nguyên từ -9,223,372,036,854,775,807 đến 9,223,372,036,854,775,807.
- Số thập phân (float): 0.5, 1.24  ..
- Kiểu kí tự (character), có thể hiểu là một chữ: 'a', '$' ..
- Kiểu chuỗi (string), có thể hiểu là một câu: "Nguyen Thanh Danh đang học C++."

---

