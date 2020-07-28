# Biến trong C#
Biến là một nơi lưu trữ giá trị của dữ liệu  
Trong C# bạn có đặt tên biến kèm theo kiểu dữ liệu của nó, trong C# thường có những kiểu dữ liệu cơ bản sau:  
- `int` số nguyên  
- `double` số thập phân  
- `char` ký tự đơn  
- `string` chuỗi kí tự  
- `bool` đúng hoặc sai  
### khai báo
Để tạo một biến, bạn phải chỉ định kiểu dữ liệu cho biến và gán cho nó một giá trị:   
Cú pháp: `type variableName = value;`  
Ví dụ: `string name = "John";`
### Thay đổi giá trị của biến  
Trong C# nếu bạn ghi đè giá trị mới lên biến hiện có, Nó sẽ lấy giá trị ở sau:  
Ví dụ:  
```int myNum = 15;
myNum = 20;
```
Kết quả sẽ là: 20  
Tuy nhiên nếu chúng ta muốn có một hằng số. Ta có thể khai báo từ khóa `const ` ở đằng trước như sau `const int myNum = 15;` lúc này myNum sẽ là 15 và không thể thay đổi được  
**Lưu ý**: Bạn không thể khai báo một biến có chứa từ khóa `const ` mà không gán giá trị. Nếu bạn làm như vậy, sẽ xảy ra lỗi: A const field requires a value to be provided.  
### phép toán (+) với biến  
- với các giá trị chuỗi kí tự hoặc kí tự. phép toán **(+)** sẽ nối 2 chuỗi lại với nhau như dưới đâu  
```
string name = "John";
Console.WriteLine("Hello " + name);
```
Kết quả: `Hello John`  
Ta cũng có thể sử dụng dấu **(+)** cho 2 biến  
```
string firstName = "John ";
string lastName = "Doe";
string fullName = firstName + lastName;
Console.WriteLine(fullName);
```
Kết quả: `John Doe`  
- Còn đối với các giá trị số phép toán **(+)** sẽ như một toán tử toán học  
```int x = 5;
int y = 6;
Console.WriteLine(x + y);
```
kết quả: `11`  

### Khai báo nhiều biến  
Để khai báo nhiều biến ta hãy phân tách các biến bằng dấu phẩy  
```int x = 5, y = 6, z = 50;
Console.WriteLine(x + y + z);
```







