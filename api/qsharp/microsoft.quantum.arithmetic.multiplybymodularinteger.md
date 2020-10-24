---
uid: Microsoft.Quantum.Arithmetic.MultiplyByModularInteger
title: MultiplyByModularInteger operation
ms.date: 10/24/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: MultiplyByModularInteger
qsharp.summary: Performs modular multiplication by an integer constant on a qubit register.
---

# MultiplyByModularInteger operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [](https://nuget.org/packages/)


Performs modular multiplication by an integer constant on a qubit register.

```qsharp
operation MultiplyByModularInteger (constMultiplier : Int, modulus : Int, multiplier : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit
```


## Description

Let us denote `modulus` by $N$ and `constMultiplier` by $a$.

## Input

### constMultiplier : [Int](xref:microsoft.quantum.lang-ref.int)

Constant by which multiplier is being multiplied. Must be co-prime to modulus.


### modulus : [Int](xref:microsoft.quantum.lang-ref.int)

The multiplication operation is performed modulo `modulus`.


### multiplier : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

The number being multiplied by a constant.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

- For the circuit diagram and explanation see Figure 7 on [Page 8