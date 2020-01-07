## if และ if-else

---

### เนื้อหา

- การใช้และวิธีเขียน `if-else`
- การใช้และวิธีเขียน `if`

---

### การใช้และวิธีเขียน `if-else`

![วิธีการเขียน](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81639725_2661247813959896_7976113302168141824_n.png?_nc_cat=102&_nc_eui2=AeHzNcp8ToPqH3eIA4W3Zf5TsM68ZHlYBKswzNGH5TYZGK4JfpeGES_5NjZtFMKVlHJ2vxQcL_sSyBPcoFi329mCQ3zCM_kRCnFy5v1V8fdSew&_nc_oc=AQmrPC45E5D7VMk-m4AB6TM05mYE9QumvSg9KB9cuDhh0giu_w8VT9moj3b25DYGNPw&_nc_ht=scontent.fkkc2-1.fna&oh=afc92e51bd21269e856d045a70d10062&oe=5EB3EB40)

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
