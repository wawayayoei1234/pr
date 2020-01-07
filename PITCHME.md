# Ternary 

---

### หัวเรื่อง


*  การใช้และการเขียน `Ternary` 


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
