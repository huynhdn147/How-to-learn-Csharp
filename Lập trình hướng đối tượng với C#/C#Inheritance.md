# Kế thừa trong C#
---
Kế thừa trong lập trình hướng đối tượng cho phép người dùng tạo một lớp (lớp kế thừa) từ một lớp có sẵn (lớp chính) kế thừa sẽ kế thừa toàn bộ tính năng của lớp chính và có thể có các tính năng bổ sung của riêng nó.  
Để kế thừa từ một lớp, sử dụng `:` ngay sau khi khai báo 1 class 
ví dụ: ` class Car : Vehicle`  
### Tại sao và khi nào nên sử dụng "Kế thừa"?
Nó rất hữu ích cho khả năng tái sử dụng code: sử dụng lại các trường và phương thức của một lớp cũ cho 1 lớp mới  
**Chú ý**: Chúng ta dễ nhầm kế thừa với đa hình. Ta sẽ phân biệt ở các bài sau  
### Lớp đóng 
Nếu bạn không muốn các lớp khác kế thừa từ một lớp, hãy sử dụng từ khóa `sealed`  
Nếu bạn cố truy cập một lớp `sealed` sẽ phát sinh lỗi  
Ví dụ: 
```sealed class Vehicle 
{
  ...
}

class Car : Vehicle 
{
  ...
}
```
Thông báo lỗi: 'Car': cannot derive from sealed type 'Vehicle'

