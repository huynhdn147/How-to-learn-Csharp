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
