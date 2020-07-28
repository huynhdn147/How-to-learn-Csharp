# Các cú pháp của C#  
### Giải thích các đoạn code `Heloo World!`

```
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
```  
Chúng ta sẽ có kết quả là dòng chữ: **Hello World**  
Ví dụ giải thích:  

- Dòng 1: `using System` có nghĩa là chúng ta có thể sử dụng các lớp từ Systemkhông gian tên.  

- Dòng 2: Một dòng trống. C # bỏ qua khoảng trắng. Tuy nhiên, nhiều dòng làm cho mã dễ đọc hơn.  

- Dòng 3: `namespace` được sử dụng để tổ chức mã của bạn và nó là một thùng chứa cho các lớp và các không gian tên khác.  

- Dòng 4: Các dấu ngoặc nhọn `{}` đánh dấu điểm bắt đầu và kết thúc của một khối mã.  

- Dòng 5: `class` là nơi chứa dữ liệu và phương thức, mang lại chức năng cho chương trình của bạn. Mỗi dòng mã chạy trong C # phải nằm trong một lớp. Trong ví dụ của chúng tôi, chúng tôi đặt tên Chương trình lớp.  
Chú ý: ** Nếu không hiểu using `System`,`namespace` và `class`. Ta nên mặc định chúng luôn xuất hiện**  
- Dòng 7: phương thức `Main`. Bất kỳ mã nào trong dấu ngoặc nhọn của nó {}sẽ được thực thi  
- Dòng 9: `Console` là 1 class của phương thức System và `WriteLine()` chính là câu lệnh in văn bản  

  **Lưu ý: Mỗi câu lệnh C # kết thúc bằng dấu chấm phẩy ;**  

**Lưu ý: C # phân biệt chữ hoa chữ thường: "MyClass" và "myclass" có ý nghĩa khác nhau.**  
---
### Cách sử dụng WriteLine hoặc Write  
`WriteLine()` và `Write()` đều là hai phương thức in ra một cái gì đó  
Sự khác biệt là `WriteLine()`in đầu ra trên một dòng mới mỗi lần, trong khi `Write()`in trên cùng một dòng và liền sau kí tự trước luôn  
Hai đoạn code sau sẽ thấy được sự khác biệt:  
```
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");
      Console.WriteLine("I will print on a new line.");

      Console.Write("Hello World! ");
      Console.Write("I will print on the same line.");    
    }
  }
}
```
Kết quả:  
***Hello World!  
I will print on a new line.  
Hello World! I will print on the same line.***







