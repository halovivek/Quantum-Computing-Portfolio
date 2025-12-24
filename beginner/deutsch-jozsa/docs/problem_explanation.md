# Deutsch–Jozsa Algorithm

## 📖 Overview
This project demonstrates the **Deutsch–Jozsa Algorithm**, an extension of Deutsch’s algorithm to `n`-bit functions.  
It shows how quantum computers can determine whether a function is **constant** or **balanced** using only **one query**, compared to the classical requirement of up to `2^(n-1) + 1` queries.

---

## 🧩 Problem Setup
We are given a function:



\[
f: \{0,1\}^n \rightarrow \{0,1\}
\]



- **Constant Function:** All inputs produce the same output (all 0s or all 1s).  
- **Balanced Function:** Exactly half of inputs produce 0, and half produce 1.  

**Classical Approach:** May require exponential queries in the worst case.  
**Quantum Approach:** Solves with just **1 query** using superposition and interference.

---

## 🖥️ Contents
- **Classical vs Quantum Intuition:** Explains why quantum can solve faster.  
- **Quantum Circuit Implementation:** Qiskit circuit for `n=2` inputs, showing oracle construction and measurement.  
- **Visualizations:** Circuit diagrams and histograms to illustrate constant vs balanced cases.  

---

## 📂 Files
- `dj_notebook.ipynb` → Jupyter Notebook with implementation and simulations.  
- `docs/problem_explanation.md` → Beginner-friendly explanation of the problem.  
- `README.md` → This documentation file.  

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install qiskit matplotlib

