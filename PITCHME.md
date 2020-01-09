## if-else-if และ if ซ้อน if

---

### เนื้อหา

- การใช้และวิธีเขียน `if-else-if`
- การใช้และวิธีเขียน `if` ซ้อน `if`

---

### การใช้และวิธีเขียน `if-else-if`

![photo](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/82161714_2627185100732307_8694372468468482048_n.png?_nc_cat=103&_nc_eui2=AeG7IaFJAE5-KLa14S28A5VmkXxaf9HGp6r5fdV4j4fBGLHYI93bhnM8ZvabhEs38J1UjBeRi5LfWva0D0t8XgxG-XfsOhVBIY9Tpuod2VOwcQ&_nc_oc=AQnhYoYU1yveBV-RZVILT076QZgCAjh9ltb4a7Om3XjSxkbb7nhRSp_RdWCJ79Pm_-Q&_nc_ht=scontent.fkkc2-1.fna&oh=aea62302d2ddcc1b43a5ce8cba3f5ea9&oe=5EAC7EB3)

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
var name = "John";
var gender = "man";

if (name == "John"){
	if (gender == "man"){
		Console.WriteLine("Hello Mr.John");
	}else{
		Console.WriteLine("Hello Ms.John");
	}
}
```

#### ผลลัพธ์

```csharp
Hello Mr.John
```

+++

### ตัวอย่างที่ 2

```csharp
var name = "John";
var gender = "woman";

if (name == "John"){
	if (gender == "man"){
		Console.WriteLine("Hello Mr.John");
	}else{
		Console.WriteLine("Hello Ms.John");
	}
}
```

#### ผลลัพธ์

```csharp
Hello Ms.John
```

---

@snap[west span-40 text-center]

#### เปรียบเทียบระหว่าง

#### if-else-if และ if ซ้อน if

@snapend

@snap[north-east span-60 text-center]

`if-else-if`

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

@snapend

@snap[south-east span-60 text-center]

`if ซ้อน if`

```csharp
var name = "John";
var gender = "man";

if (name == "John"){
	if (gender == "man"){
		Console.WriteLine("Hello Mr.John");
	}else{
		Console.WriteLine("Hello Ms.John");
	}
}
```

@snapend
