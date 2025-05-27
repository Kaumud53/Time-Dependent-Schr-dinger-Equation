# Time-Dependent Schrödinger Equation (TDSE) Simulation

This repository contains a Jupyter Notebook implementation of a one-dimensional simulation of the **Time-Dependent Schrödinger Equation (TDSE)** using finite-difference methods. It serves as an educational tool to explore wavefunction evolution in a quantum system.

## Features

- ✅ Discretizes a 1D spatial domain using a uniform grid  
- ✅ Defines an initial wavefunction using a triangular window  
- ✅ Constructs the Hamiltonian matrix using second-order finite differences  
- ✅ Diagonalizes the Hamiltonian to obtain energy eigenvalues and eigenstates  
- ✅ Projects the initial state onto the eigenbasis  
- ✅ Supports computation of time evolution (can be extended to animate or visualize dynamics)

## Getting Started

### Prerequisites

Make sure you have Python installed along with the following libraries:

```bash
pip install numpy matplotlib scipy
