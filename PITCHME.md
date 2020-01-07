## if-else-if และ if ซ้อน if

---

### เนื้อหา

- การใช้และวิธีเขียน `if-else-if`
- การใช้และวิธีเขียน `if` ซ้อน `if`

---

### การใช้และวิธีเขียน `if-else-if`

![photo](https://sv1.picz.in.th/images/2020/01/06/RB1Rry.png)

---

### การใช้และวิธีเขียน `if-else-if`

```csharp
if (เงื่อนใข A){
	// ทำในวงเล็บเมื่อเงื่อนไข A เป็นจริง
}else if (เงื่อนไข B){
	// ทำในวงเล็บเมื่อเงื่อนไข B เป็นจริง
}else if (เงื่อนไข C){
	// ทำในวงเล็บเมื่อเงื่อนใข C เป็นจริง
}else{
	// ทำในวงเล็บเมื่อไม่มีเงื่อนไขใดเป็นจริง
}
```

+++

### ตัวอย่างที่ 1

```csharp
var score = 81;

if (score > 80){
	Console.WriteLine("A");
}else if (score > 70){
	Console.WriteLine("B");
}else if (score > 60){
	Console.WriteLine("C");
}else{
	Console.WriteLine("F");
}
```

#### ผลลัพธ์

```csharp
A
```

+++

### ตัวอย่างที่ 2

```csharp
var score = 75;

if (score > 80){
	Console.WriteLine("A");
}else if (score > 70){
	Console.WriteLine("B");
}else if (score > 60){
	Console.WriteLine("C");
}else{
	Console.WriteLine("F");
}
```

#### ผลลัพธ์

```csharp
ฺฺB
```

---

### การใช้และวิธีเขียน `if` ซ้อน `if`

![](https://sv1.picz.in.th/images/2020/01/06/RBwy48.png)

---

### การใช้และวิธีเขียน `if` ซ้อน `if`

```csharp
if (เงื่อนไข A){
	// ทำในวงเล็บเมื่อเงื่อนไข A เป็นจริง
	if (เงื่อนใข B){
		// ทำในวงเล็บเมื่อเงื่อนไข B เป็นจริง
	}else{
		// ทำในวงเล็บเมื่อไม่มีเงื่อนไขใดเป็นจริง
	}
}
```

+++

### ตัวอย่างที่ 1

```csharp
var money = "yes";
var price = 20;

if (money == "yes"){
	if (price == 20){
		Console.WriteLine("You can buy");
	}else{
		Console.WriteLine("Not enough money");
	}
}
```

#### ผลลัพธ์

```csharp
You can buy
```

+++

### ตัวอย่างที่ 2

```csharp
var money = "yes";
var price = 30;

if (money == "yes"){
	if (price == 20){
		Console.WriteLine("You can buy");
	}else{
		Console.WriteLine("Not enough money");
	}
}
```

#### ผลลัพธ์

```csharp
Not enough money
```

---

### เปรียบเทียบระหว่าง if-else-if และ if ซ้อน if

![photo](https://sv1.picz.in.th/images/2020/01/06/RB9DWb.jpg)
