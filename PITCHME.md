## if-else และ if

---

### เนื้อหา

- การใช้และวิธีเขียน `if-else`
- การใช้และวิธีเขียน `if`

---

### การใช้และวิธีเขียน `if-else`

![วิธีการเขียน](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81377426_455731451763656_5266547434464477184_n.png?_nc_cat=103&_nc_eui2=AeEnEKtU5-eOsrGkMo6TQ6K5DxJOMeCRt9-kdyLdD9YjRwqTNwyXgWQ6WfOo6A--_7drUPYMoswPTEEmWPwsh4OQgPYngEoeIV21aPZVQWklyg&_nc_oc=AQl4BMK_Kt_zxxNw8YKsd7ZgVahN6Xs1WGZr9yBG0b0cI7b8G0qWc9ds9tgOuvGOFp4&_nc_ht=scontent.fkkc2-1.fna&oh=5c3612daebc428386313502e44a7ae29&oe=5E97FC96)

+++

### วิธีเขียน `if-else`

```csharp
if (เงื่ อนไข) {
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
Console.WriteLine ("Hello John!");
} else {
Console.WriteLine ("Oh,i'm sorry.");
}
```

#### ผลลัพธ์

```text
Hello John!
```

+++

### ตัวอย่างที่ 2

```csharp
var name = "Mark";

if (name == "John") {
Console.WriteLine ("Hello John!");
} else {
Console.WriteLine ("Oh,i'm sorry.");
}
```

#### ผลลัพธ์

```text
Oh,i'm sorry.
```

---

### การใช้และวิธีเขียน `if`

![วิธีการ](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81639725_2661247813959896_7976113302168141824_n.png?_nc_cat=102&_nc_eui2=AeHzNcp8ToPqH3eIA4W3Zf5TsM68ZHlYBKswzNGH5TYZGK4JfpeGES_5NjZtFMKVlHJ2vxQcL_sSyBPcoFi329mCQ3zCM_kRCnFy5v1V8fdSew&_nc_oc=AQmrPC45E5D7VMk-m4AB6TM05mYE9QumvSg9KB9cuDhh0giu_w8VT9moj3b25DYGNPw&_nc_ht=scontent.fkkc2-1.fna&oh=afc92e51bd21269e856d045a70d10062&oe=5EB3EB40)

---

### วิธีเขียน `if`

```csharp
if (เงื่ อนไข) {
	// ทำเมื่อเงื่อนไขเป็นจริง
}
```

+++

### ตัวอย่างที่ 1

```csharp
var name = "John";

if (name == "John") {
Console.WriteLine ("Hello John!");
}
Console.WriteLine ("Oh,i'm sorry.");
```

#### ผลลัพธ์

```text
Hello John!
Oh,i'm sorry.
```

---

#### เปรียบเทียบระหว่าง

#### `if-else` และ `if`

`if-else`

```csharp
if (เงื่อนไข){
	// ทำในวงเล็บเมื่อเงื่อนไขเป็นจริง
} else{
	// ทำในวงเล็บเมื่อไม่มีเงื่อนไขเป็นจริง
}
```

`if`

```csharp
if (เงื่อนไข){
	// ทำเมื่อเงื่อนไขเป็นจริง
}
```
