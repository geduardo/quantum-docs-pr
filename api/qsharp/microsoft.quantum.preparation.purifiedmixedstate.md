---
uid: Microsoft.Quantum.Preparation.PurifiedMixedState
title: PurifiedMixedState function
ms.date: 11/25/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Preparation
qsharp.name: PurifiedMixedState
qsharp.summary: "Returns an operation that prepares a a purification of a given mixed state.\rA \"purified mixed state\" refers to states of the form |ψ⟩ = Σᵢ √\U0001D45Dᵢ |\U0001D456⟩ |garbageᵢ⟩ specified by a vector of\rcoefficients {\U0001D45Dᵢ}. States of this form can be reduced to mixed states ρ ≔ \U0001D45Dᵢ |\U0001D456⟩⟨\U0001D456| by tracing over the \"garbage\"\rregister (that is, a mixed state that is diagonal in the computational basis).\r\rSee https://arxiv.org/pdf/1805.03662.pdf?page=15 for further discussion."
---

# PurifiedMixedState function

Namespace: [Microsoft.Quantum.Preparation](xref:Microsoft.Quantum.Preparation)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns an operation that prepares a a purification of a given mixed state.

```qsharp
function PurifiedMixedState (targetError : Double, coefficients : Double[]) : Microsoft.Quantum.Preparation.MixedStatePreparation
```


## Description

Uses the Quantum ROM technique to represent a given density matrix,

## Input

### targetError : [Double](xref:microsoft.quantum.lang-ref.double)

The target error $\epsilon$.


### coefficients : [Double](xref:microsoft.quantum.lang-ref.double)[]

Array of $N$ coefficients specifying the probability of basis states.



## Output : [MixedStatePreparation](xref:Microsoft.Quantum.Preparation.MixedStatePreparation)

An operation that prepares $\tilde \rho$ as a purification onto a joint

## Remarks

The coefficients provided to this operation are normalized following the

## References

- Encoding Electronic Spectra in Quantum Circuits with Linear T Complexity

## See Also

- [Microsoft.Quantum.Preparation.PurifiedMixedStateWithData](xref:Microsoft.Quantum.Preparation.PurifiedMixedStateWithData)