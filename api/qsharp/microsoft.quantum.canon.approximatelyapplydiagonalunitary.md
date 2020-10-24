---
uid: Microsoft.Quantum.Canon.ApproximatelyApplyDiagonalUnitary
title: ApproximatelyApplyDiagonalUnitary operation
ms.date: 10/24/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApproximatelyApplyDiagonalUnitary
qsharp.summary: >-
  Applies an array of complex phases to numeric basis states of a register
  of qubits, truncating small rotation angles according to a given
  tolerance.
---

# ApproximatelyApplyDiagonalUnitary operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Applies an array of complex phases to numeric basis states of a register

```qsharp
operation ApproximatelyApplyDiagonalUnitary (tolerance : Double, coefficients : Double[], qubits : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit
```


## Description

This operation implements a diagonal unitary that applies a complex phase

## Input

### tolerance : [Double](xref:microsoft.quantum.lang-ref.double)

A tolerance below which small coefficients are truncated.


### coefficients : [Double](xref:microsoft.quantum.lang-ref.double)[]

Array of up to $2^n$ coefficients $\theta_j$. The $j$th coefficient


### qubits : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

$n$-qubit control register that encodes number states $\ket{j}$ in



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

`coefficients` will be padded with elements $\theta_j = 0.0$ if

## References

- Synthesis of Quantum Logic Circuits

## See Also

- [Microsoft.Quantum.Canon.ApplyDiagonalUnitary](xref:Microsoft.Quantum.Canon.ApplyDiagonalUnitary)