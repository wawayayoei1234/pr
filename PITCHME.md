## if และ if-else

---

### หัวเรื่อง

- การใช้และวิธีเขียน `if-else`
- การใช้และวิธีเขียน `if`

---

### การใช้และวิธีเขียน `if-else`

![](https://scontent.fbkk12-1.fna.fbcdn.net/v/t1.15752-9/80509824_2382624285181242_6796320454932955136_n.png?_nc_cat=101&_nc_eui2=AeGH9zWFEw9rajFjxRkqedP3XPi-SBGOiOK-Y74sBSHBFV2WnXTgfBrjy7nkuTi7O1kDYq5JHMXSIH0ioIv1dNDlSCvoXaXnoLfCJNt8VaSeAA&_nc_oc=AQlA_cBv6PAf1KZzHdKCeEOZByqhJdo2uWQGw9F8l4xAhQyQFIOCTuEiDfAh-EYkfE8&_nc_ht=scontent.fbkk12-1.fna&oh=df7d5950f1ae31596f8fa88b208ff54e&oe=5E97EE32)

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
