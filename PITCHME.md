## else-if & nested if

---

## Agenda

@ol
*  `else-if` statement syntaxs
*  nested ` if` statement syntaxs
@olend

---

## `else-if` statement syntaxs

```csharp
if (conditionA) 
{
// Do if the conditionA is true    
} else if (conditionB) 
{
// Do if the conditionB is true    
} else if (conditionC)  
{
// Do if the conditionC is true    
} else 
{
// Or if the condition is not met    
}
```

+++

## Demo 1

```csharp
var sccore = 81;

if (score > 80) 
{
    Console.Writeline("A")
} else if (score > 70) 
{
    Console.Writeline("B")
} else if (score > 70) 
{
    Console.Writeline("B")
} else 
{
    Console.Writeline("F")
}
```

#### result

```csharp
A
```

---

##  `nested if` statement syntax 

```csharp
if (conditionA) 
{
	// Do if the conditionA is true
	if (conditionB) 
	{
	// Do if the conditionA is true		
	} else 
	{
	// Or if the condition is not met
	}
}
```

+++

## Demo 1

```csharp
var number = 1;
var numbers = 2;

if (number == 1) 
{

	if (numbers == 2) 
	{
		Console.Writeline("Hello World")
	} else 
	{
		Console.Writeline("Hello mama");
	}
}
```

#### result

```csharp
Hello World
```
