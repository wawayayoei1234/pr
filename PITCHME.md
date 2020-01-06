## if และ if-else

---

### หัวเรื่อง

- การใช้และวิธีเขียน `if-else`
- การใช้และวิธีเขียน `if`

---

### การใช้และวิธีเขียน `if-else`

![](https://scontent.fbkk12-2.fna.fbcdn.net/v/t1.15752-9/80364338_468173750506209_4044486942190993408_n.png?_nc_cat=104&_nc_eui2=AeHUH_RVHYxXhQ7Fs8s5-t9pSlA3Hk5W0_4xKaPHPjzWD6Vm1iijkcVtVhLTW362vZuyJjkHXr5hVc7t90K7HirwERHulUXtowGBktE5su5vDw&_nc_oc=AQm5k4TreAzPqL1RkfHHycyZdlq-L7UUmsuoiBGyR0g_5hlmcM78HOwfzecn0ozSQs8&_nc_ht=scontent.fbkk12-2.fna&oh=9082c1d02458b519a472c5e2a7cd04df&oe=5EA9E437)

+++

### การใช้และวิธีเขียน `if-else`

```csharp
if (เงื่อนไข) {
// ทำในวงเล็บเมื่อเงื่อนไขเป็นจริง
} else {
// ทำในวงเล็บเมื่อไม่มีเงื่อนไขเป็นจริง
}
```

+++

### ตัวอย่างที่ 1

```csharp
var name = "John";

if (name == "John") {
	Console.WriteLine("Oh, I'm looking for you John!");
} else {
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

if (name == "John") {
	Console.WriteLine("Oh, I'm looking for you John!");
} else {
	Console.WriteLine("Sorry, I thought you're John.");
}
```

#### ผลลัพธ์

```text
Sorry, I thought you're John.
```

---

### การใช้และวิธีเขียน `if` 

```csharp
if (condition) {
// Do if the condition is true
}
```

+++

### ตัวอย่างที่ 1

```csharp
var name = "John";

if (name == "John") {
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
