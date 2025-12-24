# Grover vs Classical Search

## 📖 Overview
This project demonstrates **Grover’s Algorithm**, a quantum search algorithm that provides a quadratic speedup over classical search.  
It compares query counts and success probabilities between classical search (O(N)) and Grover’s quantum search (O(√N)), including the impact of noise on quantum performance.

---

## 🧩 Problem Setup
- **Task:** Search for a target element in an unsorted database of size `N`.  
- **Classical Approach:** Requires up to `N` queries in the worst case.  
- **Quantum Approach (Grover’s):** Finds the target in approximately `√N` queries using amplitude amplification.  

---

## 🖥️ Contents
- **Classical Search Simulation:** Python function to simulate worst-case query counts.  
- **Grover’s Algorithm Implementation:** Qiskit circuit with oracle and diffusion operator.  
- **Visualizations:** Circuit diagrams, query count plots, and success probability plots.  
- **Noise Modeling:** Demonstrates how real-world quantum noise affects Grover’s success rate.  

---

## 📂 Files
- `grover_vs_classical.ipynb` → Jupyter Notebook with implementation and plots.  
- `README.md` → This documentation file.  

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install qiskit matplotlib numpy
