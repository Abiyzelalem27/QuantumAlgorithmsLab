


[![CI](https://github.com/Abiyzelalem27/quantum_algorithms/actions/workflows/python_CI.yml/badge.svg)](https://github.com/Abiyzelalem27/quantum_algorithms/actions/workflows/python_CI.yml)

[![codecov](https://codecov.io/github/Abiyzelalem27/quantum_algorithms/graph/badge.svg)](https://codecov.io/github/Abiyzelalem27/quantum_algorithms)

# Quantum Algorithms 

This repository contains implementations and simulations of quantum algorithms using Python and scientific quantum computing libraries. It explores how quantum mechanical principles such as **superposition**, **interference**, and **entanglement** enable computational advantages over classical algorithms, allowing certain problems to be solved more efficiently.

# Implemented Quantum Algorithms

## 1. Grover Search Algorithm
**Grover's Algorithm** searches for a marked element in an **unsorted database** and provides a **quadratic speedup** compared to classical search algorithms.

Classical complexity:
```
O(N)
```

Quantum complexity:
```
O(√N)
```

## 2. Quantum Fourier Transform (QFT)
The **Quantum Fourier Transform (QFT)** is the quantum analogue of the classical discrete Fourier transform. It is a key component used in many quantum algorithms.

## 3. Quantum Phase Estimation (QPE)
The **Quantum Phase Estimation algorithm** determines the **phase (eigenvalue)** associated with an eigenvector of a unitary operator. It is a central subroutine used in many advanced quantum algorithms.

## 4. Shor's Factoring Algorithm
**Shor’s Algorithm** efficiently factors large integers using quantum computation. It combines **Quantum Phase Estimation** and the **Quantum Fourier Transform** to achieve an **exponential speedup** over classical factoring algorithms.

---

# Quantum Simulations

In addition to algorithm implementations, this repository includes simulations of quantum systems and time-dependent quantum dynamics.

## Adiabatic State Preparation
This notebook demonstrates **adiabatic quantum evolution**, where a quantum system evolves slowly from an initial Hamiltonian \(H_0\) to a final Hamiltonian \(H_1\). If the evolution is slow enough, the system remains in the ground state, allowing preparation of complex quantum states.

Key topics:
- Time-dependent Hamiltonians
- Instantaneous eigenstates
- Adiabatic theorem
- Ground state preparation

## Noisy Quantum Simulations
Simulation of **noise effects in quantum systems** to study how decoherence and imperfections influence quantum algorithms.

## Rydberg Atom Simulations
Numerical simulations of **Rydberg atom systems**, which are an important physical platform for quantum computing and quantum simulation.

---

# Repository Structure

```
QuantumAlgorithmsLab/
│
├── src/
│   └── quantum_algorithms/
│       ├── __init__.py
│       ├── adiabatic.py
│       ├── deutsch_jozsa.py
│       ├── operators.py
│       ├── rydberg.py
│       └── shor_algor.py
│
├── tests/
│   ├── test_dja.py
│   └── test_op.py
│
├── notebooks/
│   ├── Adiabatic_state_preparation.ipynb
│   ├── DJA_with_error.ipynb
│   ├── deutsch_jozsa.ipynb
│   ├── Rydberg_atoms.ipynb
│   └── shor_QFT_PE.ipynb
│
├── README.md
├── CHANGELOG.md
├── LICENSE
├── pyproject.toml
└── .gitignore
```

---

# Requirements

Main dependencies:

- Python
- NumPy
- Matplotlib
- QuTiP
- SciPy

Install dependencies with:

```bash
pip install numpy matplotlib qutip scipy
```

---

# References

- Nielsen & Chuang — *Quantum Computation and Quantum Information*
- QuTiP Documentation — https://qutip.org/docs/

---

# Author 

**Abiy Zelalem Tegegne** 

GitHub:  
https://github.com/Abiyzelalem27