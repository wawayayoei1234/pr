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
