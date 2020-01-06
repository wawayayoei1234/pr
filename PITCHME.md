# Ternary 

---

### หัวเรื่อง


*  การใช้และการเขียน`Ternary` 


---

###  การใช้และการเขียน`Ternary` 

```csharp
result = condition ? valueIfTrue: valueIfFalse;
```

+++

### ตัวอย่างที่ 1

```csharp
var vat = 7.0;
var price = 1000;

 amount = vat > 0.0 ? price * (100 + vat) / 100 : price;
```

#### ผลลัพธ์

```csharp
1070
```
+++
### ตัวอย่างที่ 2

```csharp
var vat = 0.0;
var price = 1000;

 amount = vat > 0.0 ? price * (100 + vat) / 100 : price;
```

#### ผลลัพธ์

```csharp
1000
```
---
### เปรียบเทียบ 

@snap[west span-50]  
double vat = 7.0; // VAT 7%
double amount;
double price = 1000;

if (vat > 0.0)
{
     amount = price * (100 + vat) / 100;
} else {
     amount = price;
}
Console.WriteLine("Product price : "+amount);
@snapend 

@snap[east span-50]  
double vat = 7.0; // VAT 7%
double amount;
double price = 1000;
amount = (vat > 0.0) ? price * (100 + vat) / 100 : price;
Console.WriteLine("Product price : " + amount);
@snapend 
