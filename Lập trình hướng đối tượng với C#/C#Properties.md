# Tính đóng gói trong C# (Get and Set)
---
### Khái niệm về *đóng gói*
- Ý nghĩa của việc đóng gói là đảm bảo dữ liệu quan trọng sẽ được ẩn khỏi người dùng. Để đạt được điều này ta cần làm những bước sau:  
  - Khai báo các biến/thuộc tính ở trong `private`
  - cung cấp các phương thức dưới dạng `public` dùng để `set` và `get` các giá trị của một biến/thuộc tính  

### Các tính chất của đóng gói  
Vi `private` chỉ có thể được truy cập trong cùng một lớp (một lớp bên ngoài không có quyền truy cập vào nó) cho nên
như đã nói ở trên để truy cập vào các biến `private` ta cần tạo các phương thức `set` và `get` để truy cập  
ví dụ:  
```
class Person
{
  private string name; // field

  public string Name   // property
  {
    get { return name; }   // get method
    set { name = value; }  // set method
  }
}
class Program
{
  static void Main(string[] args)
  {
    Person myObj = new Person();
    myObj.Name = "Liam";
    Console.WriteLine(myObj.Name);
  }
}
  ```
 Kết quả: Liam  
 ### Thuộc tính tự động  
 thay vì chúng ta viết như trên ta có thể rút gọn như sau  
 ```
 class Person
{
  public string Name  // property
  { get; set; }
}
```
### Lợi ích khi đóng gói 
- Kiểm soát các thành phần trong 1 lớp tốt hơn, giảm khả năng làm loạn code
- Tăng cường bảo mật dữ liệu  
- có thể thay đổi một phần code mà không ảnh hưởng đến các phần khác
  


