---
uid: Microsoft.Quantum.Math.ExpModL
title: ExpModL function
ms.date: 10/24/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Math
qsharp.name: ExpModL
qsharp.summary: >-
  Returns an integer raised to a given power, with respect to a given
  modulus.
---

# ExpModL function

Namespace: [Microsoft.Quantum.Math](xref:Microsoft.Quantum.Math)

Package: [](https://nuget.org/packages/)


Returns an integer raised to a given power, with respect to a given

```qsharp
function ExpModL (expBase : BigInt, power : BigInt, modulus : BigInt) : BigInt
```


## Description

Let us denote expBase by $x$, power by $p$ and modulus by $N$.

## Input

### expBase : [BigInt](xref:microsoft.quantum.lang-ref.bigint)




### power : [BigInt](xref:microsoft.quantum.lang-ref.bigint)




### modulus : [BigInt](xref:microsoft.quantum.lang-ref.bigint)





## Output : [BigInt](xref:microsoft.quantum.lang-ref.bigint)



## Remarks

Takes time proportional to the number of bits in `power`, not the `power` itself.