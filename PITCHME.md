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
if (condition) {
// Do if the condition is true
} else {
// Or if the condition is not met
}
```

+++

### Demo 1

```csharp
var name = "John";

if (name == "John") {
	Console.WriteLine("Oh, I'm looking for you John!");
} else {
	Console.WriteLine("Sorry, I thought you're John.");
}
```

#### result

```text
Oh, I'm looking for you John!
```

+++

### Demo 2

```csharp
var name = "";

if (name == "John") {
	Console.WriteLine("Oh, I'm looking for you John!");
} else {
	Console.WriteLine("Sorry, I thought you're John.");
}
```

#### result

```text
Sorry, I thought you're John.
```

---

### `if` Statement Syntax

```csharp
if (condition) {
// Do if the condition is true
}
```

+++

### Demo 1

```csharp
var name = "John";

if (name == "John") {
	Console.WriteLine("Oh, I'm looking for you John!");
}
Console.WriteLine("Sorry, I thought you're John.");
```

#### result

```text
Oh, I'm looking for you John!
Sorry, I thought you're John.
```

##### ถึง name จะเป็นจริงหรือไม่ _"Sorry, I thought you're John."_ ยังแสดงผลอยู่ดี

---

### compare

@snap[text-left]
if-else
@snapend

```csharp
var name = "Joe";

if (name == "John") {
	Console.WriteLine("Oh, I'm looking for you John!");
} else {
	Console.WriteLine("Sorry, I thought you're John.");
}
```

@snap[text-left]
if
@snapend

```csharp
var name = "John";

if (name == "John") {
	Console.WriteLine("Oh, I'm looking for you John!");
}
Console.WriteLine("Sorry, I thought you're John.");
```

+++

### compare

@snap[text-left]
result if-else
@snapend

```text
Sorry, I thought you're John.
```

@snap[text-left]
result if
@snapend

```text
Oh, I'm looking for you John!
Sorry, I thought you're John.
```
