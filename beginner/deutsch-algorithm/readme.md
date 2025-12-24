# Deutsch’s Algorithm

## 📖 Overview
This project demonstrates **Deutsch’s Algorithm**, one of the simplest quantum algorithms.  
It shows how a quantum computer can determine whether a function is **constant** or **balanced** using only **one query**, compared to the classical requirement of two queries.

---

## 🧩 Problem Setup
We are given a function:



\[
f: \{0,1\} \rightarrow \{0,1\}
\]



- **Constant Function:** Always returns the same output (0 or 1).  
- **Balanced Function:** Returns 0 for one input and 1 for the other.  

**Classical Approach:** Requires 2 queries (check both inputs).  
**Quantum Approach:** Solves with just 1 query using superposition and interference.

---

## 🖥️ Contents
- **Classical Implementation:** Python function that tests both inputs.  
- **Quantum Implementation:** Qiskit circuit that encodes the oracle and uses Hadamard gates to exploit quantum parallelism.  
- **Visualizations:** Circuit diagrams and measurement histograms to show results.  

---

## 📂 Files
- `deutsch_notebook.ipynb` → Jupyter Notebook with classical and quantum implementations.  
- `README.md` → This documentation file.  

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install qiskit matplotlib
