## else-if และ if ซ้อน if

---

### หัวเรื่อง

*  การใช้และวิธีเขียน `else-if`  
*  การใช้และวิธีเขียน ` if` ซ้อน `if` 

---

### การใช้และวิธีเขียน `else-if` เบื่องต้น

![](https://sv1.picz.in.th/images/2020/01/06/RBtwgV.png)
---

### การใช้และวิธีเขียน `else-if` เบื่องต้น

```csharp
if (เงื่อนใข A){
// ทำในวงเล็บเมื่อเงื่อนใข A เป็นจริง    
}else if (เงื่อนใข B){
// ทำในวงเล็บเมื่อเงื่อนใข B เป็นจริง     
}else if (เงื่อนใข C){
// ทำในวงเล็บเมื่อเงื่อนใข C เป็นจริง    
}else{
// ทำในวงเล็บเมื่อไม่มีเงื่อนใขใดเป็นจริง    
}
```

+++

### ตัวอย่างที่ 1

```csharp
    var score = 81;
    if (score > 80){
        Console.WriteLine ("A");
        }else if (score > 70){
            Console.WriteLine ("B");
        }else if (score > 70){
            Console.WriteLine ("C");
        }else{
            Console.WriteLine ("F");
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
        Console.WriteLine ("A");
        }else if (score > 70){
            Console.WriteLine ("B");
        }else if (score > 70){
            Console.WriteLine ("C");
        }else{
            Console.WriteLine ("F");
        }
```

#### ผลลัพธ์

```csharp
ฺฺB
```
---

### การใช้และวิธีเขียน  ` if` 

```csharp
if (เงื่อนใข A){
	// ทำในวงเล็บเมื่อเงื่อนใข A เป็นจริง
	if (เงื่อนใข B){
	// ทำในวงเล็บเมื่อเงื่อนใข B เป็นจริง		
	}else{
	// ทำในวงเล็บเมื่อไม่มีเงื่อนใขใดเป็นจริง
	}
}
```

+++

### ตัวอย่างที่ 1

```csharp

var money = yes;
var price = 20;

if (money == yes){
 if (price == 20){
    	Console.WriteLine("You can buy");
    }else{
    	Console.WriteLine("Not enough money");
  }
}
```

#### ผลลัพธ์

```csharp
Hello World
```
+++
### ตัวอย่างที่ 2

```csharp
    var money = "yes";
    var price = 30;
    if (money == "yes") {
        if (price == 30) {
         Console.WriteLine ("You can buy");
        }else {
         Console.WriteLine ("Not enough money");
        }
    }
```

#### ผลลัพธ์

```csharp
Bey Bey World
```
---

### เปรียบเทียบ

![photo](https://sv1.picz.in.th/images/2020/01/06/RB9DWb.jpg)