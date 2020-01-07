## if-else-if และ if ซ้อน if

---

### เนื้อหา

- การใช้และวิธีเขียน `if-else-if`
- การใช้และวิธีเขียน `if` ซ้อน `if`

---

### การใช้และวิธีเขียน `if-else-if`

![photo](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81345507_468088657189752_2210022799941042176_n.png?_nc_cat=108&_nc_eui2=AeEoyzTQonT0EJu8S5vVYQojF6ivSgPl1FQo-7EBGS1WAPzsiaXHLiS8f45tjFqMcVVnKUgIy7KuxycaqpF7KZxvWl9ppjsy0HabiOtERe5hSQ&_nc_oc=AQke_FyOsD_IeUfyJJ5STmKnyQOYkwEkDg1SWsezjm_K34nSUphqafqPbI5c2pgoZL8&_nc_ht=scontent.fkkc2-1.fna&oh=8d18fe74da10641a787fff31fb35a5b3&oe=5EB462D3)

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

![](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/81437743_468883894035422_2951059492072062976_n.png?_nc_cat=110&_nc_eui2=AeHxrJIIJwRgQ5DZduR4EQl4GVw0Eux6InMPnYO-VzqzgPt31aWatcrA8mndOQG6b5ImW5l17uoNJz5pq-NdTBBAIr26KLAvOQOFGVfqzHKS3g&_nc_oc=AQnsGW_jW18M5wTgzPvrMTCRaheYuPOwz0cFHZKIrKs7MgmoL_HDuTXHCWwten8IvU8&_nc_ht=scontent.fkkc2-1.fna&oh=1e53231c50f5873b3be1d64662534ec1&oe=5E9D8422)

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
