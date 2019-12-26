# Ternary 

---

## Agenda

@ol
*  `Ternary` statement syntaxs
@olend

---

##  `Ternary` statement syntaxs

```csharp
result = condition ? valueIfTrue: valueIfFalse;
```

+++

## Demo 1

```csharp
var vat = 7.0;
var price = 1000;

var amount = vat > 0.0 ? price * (100 + vat) / 100 : price;
```

#### result

```csharp
1070
```
