# Ternary 

---

### เนื้อหา


*  การใช้และการเขียน `Ternary` 


---

###  การใช้และการเขียน `Ternary` 

```csharp
var result = condition ? valueIfTrue: valueIfFalse;
```

+++

### ตัวอย่างที่ 1

```csharp
var vat = 7.0;
var price = 1000;

var amount = vat > 0.0 ? price * (100 + vat) / 100 : price;
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

var amount = vat > 0.0 ? price * (100 + vat) / 100 : price;
```

#### ผลลัพธ์

```csharp
1000
```

---

@snap[west span-40 text-center]

#### เปรียบเทียบระหว่าง

#### `Ternary` 
#### และ `if-else`

@snapend

@snap[north-east span-60 text-center]

`Ternary`

```csharp
var vat = 0.0;
var price = 1000;

var amount = vat > 0.0 ? 
    price * (100 + vat) / 100 : price;
```

@snapend

@snap[south-east span-60 text-center]

`if-else`

```csharp
var vat = 0.0;
var price = 1000;
double amount = 0;

if (vat > 0.0){
    amount = price * (100 + vat) / 100;
} else{
    amount = price;
}
Console.Writeline(amount);
```

@snapend
