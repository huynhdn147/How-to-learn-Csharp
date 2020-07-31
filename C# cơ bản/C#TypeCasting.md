# Ép kiểu trong C#  
***
Trong C# có hai loại ép kiểu **Ép mặc định(Ép ngầm)** và **ép thủ công**  
### Ép ngầm  
Ép kiểu ngầm trong C# tự động được thực hiện khi chuyển loại có kích thước nhỏ hơn sang kích thước lớn hơn  
```
int myInt = 9;
double myDouble = myInt;      

Console.WriteLine(myInt);      
Console.WriteLine(myDouble);
```
kết quẩ: 9 9
###
