---
uid: Microsoft.Quantum.Arithmetic.EvaluateEvenPolynomialFxP
title: EvaluateEvenPolynomialFxP operation
ms.date: 10/24/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: EvaluateEvenPolynomialFxP
qsharp.summary: Evaluates an even polynomial in a fixed-point representation.
---

# EvaluateEvenPolynomialFxP operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [](https://nuget.org/packages/)


Evaluates an even polynomial in a fixed-point representation.

```qsharp
operation EvaluateEvenPolynomialFxP (coefficients : Double[], fpx : Microsoft.Quantum.Arithmetic.FixedPoint, result : Microsoft.Quantum.Arithmetic.FixedPoint) : Unit
```


## Input

### coefficients : [Double](xref:microsoft.quantum.lang-ref.double)[]

Coefficients of the even polynomial as a double array, i.e., the array


### fpx : [FixedPoint](xref:Microsoft.Quantum.Arithmetic.FixedPoint)

Input fixed-point number for which to evaluate the polynomial.


### result : [FixedPoint](xref:Microsoft.Quantum.Arithmetic.FixedPoint)

Output fixed-point number which will hold $P(x)$. Must be in state



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)
