## if-else-if และ if ซ้อน if

---

### เนื้อหา

- การใช้และวิธีเขียน `if-else-if`
- การใช้และวิธีเขียน `if` ซ้อน `if`

---

### การใช้และวิธีเขียน `if-else-if`

![photo](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81353008_531141174160000_8947493479840219136_n.png?_nc_cat=111&_nc_eui2=AeHz4e2SJoiBEMb0oTph-WmQlSKbrWYJxuvcs159YsigCih-b-uPVHvoHJkDcl4GgQVtXPycRjxGGxnQbQ4W3sg5RDkSEDCmqV09CYC4Ukrj5w&_nc_oc=AQnCkmReF5ksq9G-Do-45-IBYPRKffovlUGrITdTQu28DZiBEt2ZFlfQE9r3SsXH5oI&_nc_ht=scontent.fkkc2-1.fna&oh=00fda152368aacf8998122e72615f355&oe=5E990340)

---

### วิธีเขียน `if-else-if`

```csharp
if (เงื่อนไข A){
	// ทำในวงเล็บเมื่อเงื่อนไข A เป็นจริง
}else if (เงื่อนไข B){
	// ทำในวงเล็บเมื่อเงื่อนไข B เป็นจริง
}else if (เงื่อนไข C){
	// ทำในวงเล็บเมื่อเงื่อนไข C เป็นจริง
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

![](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81271098_461773167842810_8568102122183196672_n.png?_nc_cat=102&_nc_eui2=AeHpCHhr5lUrzZCGTgzRthmgo2DgAhFzVrh8EAfJPg-YcK5Kgfw87KdygNPoiJnCZ-rjfYEZolnR-xlUt6d20sjbl7m6egTvc4PoQYDbfK479w&_nc_oc=AQnCgrEnwsXd-vvKEkl8ZgsCiffVSQSqT3sZpuuDxkoXA1m3lN9o1FQ_9oxT7p8degA&_nc_ht=scontent.fkkc2-1.fna&oh=eed5bcc654024987458f46ccb8e4825d&oe=5EB218EC)

---

### วิธีเขียน `if` ซ้อน `if`

```csharp
if (เงื่อนไข A){
	if (เงื่อนไข B){
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
		Console.WriteLine("No Money");
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
		Console.WriteLine("No money");
	}
}
```

#### ผลลัพธ์

```csharp
No Money
```
