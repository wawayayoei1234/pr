## if และ if-else

---

### หัวเรื่อง

- การใช้และวิธีเขียน `if-else`
- การใช้และวิธีเขียน `if`

---

### การใช้และวิธีเขียน `if-else`

![](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81327675_527867397814703_277030389933932544_n.png?_nc_cat=104&_nc_ohc=4egw922EmggAQknmMoD6WtS2PUUzKAeHFGfgwOVB0Erzsja3Zu8IZNXMA&_nc_ht=scontent.fkkc2-1.fna&oh=abb3fc328cf05936cd789cb62daa263a&oe=5EA42B34)

+++

### การใช้และวิธีเขียน `if-else`

```csharp
if (เงื่อนไข){
// ทำในวงเล็บเมื่อเงื่อนไขเป็นจริง
} else{
// ทำในวงเล็บเมื่อไม่มีเงื่อนไขเป็นจริง
}
```

+++

### ตัวอย่างที่ 1

```csharp
var name = "John";

if (name == "John"){
	Console.WriteLine("Oh, I'm looking for you John!");
} else{
	Console.WriteLine("Sorry, I thought you're John.");
}
```

#### ผลลัพธ์

```text
Oh, I'm looking for you John!
```

+++

### ตัวอย่างที่ 2

```csharp
var name = "Mark";

if (name == "John"){
	Console.WriteLine("Oh, I'm looking for you John!");
} else{
	Console.WriteLine("Sorry, I thought you're John.");
}
```

#### ผลลัพธ์

```text
Sorry, I thought you're John.
```

---

### การใช้และวิธีเขียน `if` 
![](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/80838713_2480832262185612_6068699028726480896_n.png?_nc_cat=105&_nc_ohc=BFgUt8A0w4wAQnrsUkr0Rf7KKEUwwVwtjGbaijNcEwisAoRrZfruTFGCA&_nc_ht=scontent.fkkc2-1.fna&oh=0e67b051df570583cf2f1027373f6a0f&oe=5E912530)

---

### การใช้และวิธีเขียน `if` 

```csharp
if (เงื่อนไข) {
// ทำเมื่อเงื่อนไขเป็นจริง
}
```

+++

### ตัวอย่างที่ 1

```csharp
var name = "John";

if (name == "John"){
	Console.WriteLine("Oh, I'm looking for you John!");
}
Console.WriteLine("Sorry, I thought you're John.");
```

#### ผลลัพธ์

```text
Oh, I'm looking for you John!
Sorry, I thought you're John.
```
---

### เปรียบเทียบ
![](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/82266638_1197111010495309_287991962517110784_n.jpg?_nc_cat=106&_nc_ohc=gL4-Xr15_6UAQk5JkTOL6wVWKBT1xyyQL4gcgyM-WtONPw_vJMSuZWmCw&_nc_ht=scontent.fkkc2-1.fna&oh=bb8a58067b205b158399281306a5f527&oe=5E947EA2)