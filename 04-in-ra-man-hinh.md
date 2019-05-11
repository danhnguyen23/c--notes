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

---

**Làm tròn số thập phân trong C++**

Ví dụ muốn in ra số f với x chữ số thập phân, ta sử dụng:

```C++
// Nhớ có #include <iomanip>
cout << fixed << setprecision(x) << f;
```

---

**Bài tập**:

- [2.1. In tên "Nguyễn Thành Danh" ra màn hình.](https://repl.it/@VeirPlays/DefinitiveQuarterlyAddons)
- [2.2. In số 1 ra màn hình.](https://repl.it/@VeirPlays/22)
- [2.3. In chữ D ra màn hình.](https://repl.it/@VeirPlays/23)
- [2.4. In số thập phân 4.7 ra màn hình.](https://repl.it/@VeirPlays/24)
- [2.5. In nội dung sau ra màn hình:](https://repl.it/@VeirPlays/25)
  ```
  Thành
  Danh
  ```

