## else-if & Nested if

---

## หัวเรื่อง

*  `else-if` statement syntaxs
*  nested ` if` statement syntaxs

---

## การใช้และวิธีเขียน `else-if` เบื่องต้น

```csharp
if (conditionA) {
// Do if the conditionA is true    
} else if (conditionB) {
// Do if the conditionB is true    
} else if (conditionC)  {
// Do if the conditionC is true    
} else {
// Or if the condition is not met    
}
```

+++

## ตัวอย่างที่ 1

```csharp
var sccore = 81;

if (score > 80) {
    Console.Writeline("A")
} else if (score > 70) {
    Console.Writeline("B")
} else if (score > 70) {
    Console.Writeline("C")
} else {
    Console.Writeline("F")
}
```

#### ผลลัพธ์

```csharp
A
```
+++
## ตัวอย่างที่ 2

```csharp
var sccore = 75;

if (score > 80) {
    Console.Writeline("A")
} else if (score > 70) {
    Console.Writeline("B")
} else if (score > 70) {
    Console.Writeline("C")
} else {
    Console.Writeline("F")
}
```

#### ผลลัพธ์

```csharp
ฺฺB
```
---

## การใช้และวิธีเขียน  ` if` 

```csharp
if (conditionA) 
{
	// Do if the conditionA is true
	if (conditionB) {
	// Do if the conditionA is true		
	} else {
	// Or if the condition is not met
	}
}
```

+++

## ตัวอย่างที่ 1

```csharp
var number = 1;

if (number == 1) 
{
	if (number == 1) {
		Console.Writeline("Hello World")
	} else {
		Console.Writeline("Hello Mama");
	}
}
```

#### ผลลัพธ์

```csharp
Hello World
```
+++
## ตัวอย่างที่ 2

```csharp
var number = 1;

if (number == 1) 
{
	if (number == 2) {
		Console.Writeline("Hello World")
	} else {
		Console.Writeline("Hello Mama");
	}
}
```

#### ผลลัพธ์

```csharp
Hello Mama
```
---
### เปรียบเทียบ

![]()