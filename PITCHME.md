## If & if-else

---
## Agenda

@ol
* `if-else` Statement Syntaxs
* `if` Statement Syntaxs

@olend

---
##  `if else` Statement Syntax 
![](https://scontent.fkkc2-1.fna.fbcdn.net/v/t1.15752-9/80838713_2480832262185612_6068699028726480896_n.png?_nc_cat=105&_nc_ohc=Jtv49Vm6ugYAQlNCT6fJGkfwaI_BDcyf0W5CiZ-PXtKujnl7FWiQzdC4g&_nc_ht=scontent.fkkc2-1.fna&oh=ab75bb0e994bb854dea704be3fc2f6db&oe=5E699830)
---
##  `if else` Statement Syntax 

```csharp
if (condition) {
// Do if the condition is true
} else {
// Or if the condition is not met
}
```

+++

## Demo 1

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

## Demo 2

```csharp
var name = "Joe";

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
##  `if` Statement Syntax 

```csharp
if (condition) {
// Do if the condition is true
}
```
+++

## Demo 1

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
##### ถึง name จะเป็นจริงหรือไม่ *"Sorry, I thought you're John."* ยังแสดงผลอยู่ดี
---
## compare
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
## compare
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