# Các lớp và đối tượng C#  
--- 
### Tạo một lớp trong C# 
để tạo một lớp, ta sử dụng từ khóa `class`:  
ví dụ: Tạo một lớp có tên " Car" với một biến color:
```
class Car 
{
  string color = "red";
}
```
### Tạo một đối tượng  
Một đối tượng được tạo ra từ một lớp. Chúng ta đã tạo lớp có tên `Car`, vì vậy bây giờ chúng ta có thể sử dụng lớp này để tạo đối tượng.  
Để tạo một đối tượng `Car`, chỉ định tên lớp, theo sau là tên đối tượng và sử dụng từ khóa **new**:  
```
class Car 
{
  string color = "red";

  static void Main(string[] args)
  {
    Car myObj = new Car();
    Console.WriteLine(myObj.color);
  }
}
```
### Tạo nhiều đối tượng
Ta có thể tạo ra nhiều đối tượng khác nhau từ một lớp  
ví dụ:  
```
class Car
{
  string color = "red";
  static void Main(string[] args)
  {
    Car myObj1 = new Car();
    Car myObj2 = new Car();
    Console.WriteLine(myObj1.color);
    Console.WriteLine(myObj2.color);
  }
}
```
Sử dụng nhiều lớp  
Bạn cũng có thể tạo một đối tượng của một lớp và truy cập nó trong một lớp khác. Điều này thường được sử dụng để tổ chức các lớp tốt hơn (một lớp có tất cả các trường và phương thức, trong khi lớp kia giữ Main() phương thức.





