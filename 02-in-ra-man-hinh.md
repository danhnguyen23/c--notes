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

- Số nguyên (integer): 0, 1 ..
- Số thập phân (float): 0.5, 1.24  ..
- Kiểu kí tự (character), có thể hiểu là một chữ: 'a', '$' ..
- Kiểu chuỗi (string), có thể hiểu là một câu: "Nguyen Thanh Danh đang học C++."

---

**In giá trị ra màn hình**

Để in một giá trị nào đó ra màn hình, ta dùng `cout` với cú pháp sau đây:

```
cout << GIÁ_TRỊ_MUỐN_IN;
```

`cout` nằm trong thư việc `iostream`, nên muốn sử dụng nó, ta phải khai báo thư viện này
cho chương trình C++ biết với cú pháp `include` sau:

```C++
#include <iostream>
using namespace std;
```

Lấy ví dụ, [đây](https://repl.it/@VeirPlays/In-ten-ra-man-hinh) là một chương trình in tên ra màn hình.

---

**Kí tự xuống dòng**

Kí tự xuống dòng là `\n`.

**Bài tập**:

- [2.1. In tên "Nguyễn Thành Danh" ra màn hình.](https://repl.it/@VeirPlays/DefinitiveQuarterlyAddons)
- [2.2. In số 1 ra màn hình.](https://repl.it/@VeirPlays/22)
- [2.3. In chữ D ra màn hình.](https://repl.it/@VeirPlays/23)
- [2.4. In số thập phân 4.7 ra màn hình.](https://repl.it/@VeirPlays/24)
- 2.5. In nội dung sau ra màn hình:
  ```
  Thành
  Danh
  ```
