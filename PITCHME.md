## if และ if-else

---

### เนื้อหา

- การใช้และวิธีเขียน `if-else`
- การใช้และวิธีเขียน `if`

---

### การใช้และวิธีเขียน `if-else`

![วิธีการเขียน]()

+++

### วิธีเขียน `if-else`

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

![วิธีการ]()

---

### วิธีเขียน `if`

```csharp
if (เงื่อนไข){
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
