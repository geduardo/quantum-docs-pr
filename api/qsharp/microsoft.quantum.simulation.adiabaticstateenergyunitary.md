---
uid: Microsoft.Quantum.Simulation.AdiabaticStateEnergyUnitary
title: AdiabaticStateEnergyUnitary operation
ms.date: 10/24/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Simulation
qsharp.name: AdiabaticStateEnergyUnitary
qsharp.summary: >-
  Performs state preparation by applying a
  `statePrepUnitary` on the input state, followed by adiabatic state
  preparation using a `adiabaticUnitary`, and finally phase estimation
  with respect to `qpeUnitary`on the resulting state using a
  `phaseEstAlgorithm`.
---

# AdiabaticStateEnergyUnitary operation

Namespace: [Microsoft.Quantum.Simulation](xref:Microsoft.Quantum.Simulation)

Package: [](https://nuget.org/packages/)


Performs state preparation by applying a

```qsharp
operation AdiabaticStateEnergyUnitary (statePrepUnitary : (Qubit[] => Unit), adiabaticUnitary : (Qubit[] => Unit), qpeUnitary : (Qubit[] => Unit is Adj + Ctl), phaseEstAlgorithm : ((Microsoft.Quantum.Oracles.DiscreteOracle, Qubit[]) => Double), qubits : Qubit[]) : Double
```


## Input

### statePrepUnitary : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) 

An oracle representing state preparation for the initial dynamical


### adiabaticUnitary : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) 

An oracle representing the adiabatic evolution algorithm to be used


### qpeUnitary : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj + Ctl

An oracle representing a unitary operator $U$ representing evolution


### phaseEstAlgorithm : ([DiscreteOracle](xref:Microsoft.Quantum.Oracles.DiscreteOracle),[Qubit](xref:microsoft.quantum.lang-ref.qubit)[]) => [Double](xref:microsoft.quantum.lang-ref.double) 

An operation that performs phase estimation on a given unitary operation.


### qubits : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

A register of qubits to be used to perform the simulation.



## Output : [Double](xref:microsoft.quantum.lang-ref.double)

An estimate $\hat{\phi}$ of the ground state energy $\phi$