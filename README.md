# Quantum Computing Applications for Flight Trajectory Optimization

An academic mini-project exploring quantum optimization algorithms using **Qiskit** to solve flight path selection and waypoint routing under airspace constraints.

## 📌 Project Overview
Flight trajectory optimization is a complex combinatorial problem. This project formulates routing and collision-avoidance constraints into a **QUBO (Quadratic Unconstrained Binary Optimization)** matrix and solves them using the **QAOA (Quantum Approximate Optimization Algorithm)** framework on Qiskit simulators.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Quantum SDK:** IBM Qiskit
- **Simulation:** Qiskit Aer (`AerSimulator`)
- **Optimization:** SciPy (`COBYLA`)
- **Visualization:** Matplotlib, Qiskit Visualization Modules

## 📊 Key Components & Visualizations
1. **Parameterized Quantum Circuits:** Utilizes Hadamard ($H$) initialization, CNOT entanglement layers, and phase/mixer rotation gates ($R_z, R_x$).
2. **Optimization Convergence:** Tracks cost reduction over variational iterations to minimize flight path penalties.
3. **Probability Distribution:** Outputs measurement histograms to identify the most probable binary solutions corresponding to optimal flight paths.

## 🚀 How to Run
You can run this project directly in your browser via Google Colab:
- *(Optional: Add your Google Colab badge or link here)*
- Open the `.ipynb` notebook file in this repository and run all cells sequentially.

---
*Developed as part of coursework and practical exploration in Quantum Computing.*
