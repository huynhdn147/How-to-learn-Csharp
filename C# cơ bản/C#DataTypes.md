# Kiểu dữ liệu trong C#
Trong C# có hai loại kiểu dữ liệu sau: Dữ liệu do người từ định nghĩa và dữ liệu có sẵn.  
### Các kiểu dữ liệu có sẵn  
Kiểu dữ liệu có sẵn là các kiểu dữ liệu phổ biến, được định nghĩa trong chính ngôn ngữ. Dưới bảng sau là các kiểu dữ liệu thông dụng nhất  
| Kiểu dữ liệu | Kích thước | Ghi chú  |
|:-------|:------:|:-------|
|  int	  |  4 byte  | Lưu toàn bộ số từ -2,147,483,648 đến 2,147,483,647  |
|  long	 |  8 byte  | Lưu trữ toàn bộ số từ -9,223,372,036,854,775,809 đến 9,223,372,036,854,775,807|
|  float |  4 byte  | Lưu trữ số thập phân. Đủ để lưu trữ 6 đến 7 chữ số thập phân|
|  double	 |  8 byte  | Lưu trữ số thập phân. Đủ để lưu trữ 15 chữ số thập phân|
|  bool	 |  1 bit  | Lưu giá trị đúng hoặc sai|
|  char	 |  2 byte  | Lưu trữ một ký tự / chữ cái, được bao quanh bởi các dấu ngoặc đơn|
|  string	 |  2 byte cho mỗi ký tự   | Lưu trữ một chuỗi các ký tự, được bao quanh bởi dấu ngoặc kép|

### Các ví dụ về kiểu dữ liệu  
#### Các kiểu dữ liệu số
Các loại số được chia thành hai nhóm:

Các kiểu số nguyên lưu số nguyên, dương hoặc âm (chẳng hạn như 123 hoặc -456), không có số thập phân. Các loại hợp lệ là `int` và `long`.tùy vào giá trị số để bạn chọn kiểu dữ kiệu thích hợp.

Các kiểu dấu phẩy động biểu thị các số có có dạng số thập phân, chứa một hoặc nhiều số thập phân đằng sau dấu phẩy . Các loại hợp lệ là `float` và `double`.  
Ghi chú nhỏ: Nên sử dụng `float` hay `double`?  
Độ chính xác đằng sau giá trị dấu phẩy của hai kiểu dữ kiệu trên là khác nhau.  Độ chính xác `float` chỉ là sáu hoặc bảy chữ số thập phân, trong khi `double` có độ chính xác khoảng 15 chữ số. Do đó, an toàn hơn để sử dụng `double` cho hầu hết các tính toán.  

#### Kiểu dữ liệu Booleans  
kiểu dữ liệu boolean được khai báo bằng từ khóa `bool`. Trả về một trong hai kết quả là `true`hoặc `false` tương ứng với hai giá trị **1** hoặc **0**:  
#### Kiểu dữ liệu char  
Kiểu dữ liệu` char` được dùng để khai báo một kí tự. Và kí tự đó phải được bao quanh bằng dấu ngoặc đơn(''):  
Ví dụ:  
`char myGrade = 'B';`  
#### Kiểu dữ liệu String  
Kiểu dữ liệu `String` được dùng để khai báo một chuỗi kí tự. và được bao quanh bằng dấu ngoặc kép(""):
Ví dụ:
`string greeting = "Hello World";`  
---
[Bài tiếp theo: Ép kiểu trong C#](https://github.com/huynhdn147/How-to-learn-Csharp/blob/master/C%23%20c%C6%A1%20b%E1%BA%A3n/README.md)



