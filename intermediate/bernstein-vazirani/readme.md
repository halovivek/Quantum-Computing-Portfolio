# Bernstein–Vazirani Problem

## 📖 Overview
This project demonstrates the **Bernstein–Vazirani Algorithm**, which efficiently finds a hidden binary string `s`.  
The function is defined as:



\[
f(x) = (x \cdot s) \mod 2
\]



where `x` is an `n`‑bit input and `s` is the secret `n`‑bit string.  
Quantum parallelism allows us to uncover the entire string in **one query**, compared to the classical requirement of `n` queries.

---

## 🧩 Problem Setup
- **Input:** `x` (n‑bit string)  
- **Secret:** `s` (n‑bit hidden string)  
- **Output:** `f(x)` = parity of the dot product of `x` and `s`.  

**Example:**  
If `s = 101` and `x = 011`:  


\[
(0 \cdot 1) + (1 \cdot 0) + (1 \cdot 1) = 1 \quad \Rightarrow \quad f(x) = 1
\]



---

## 🖥️ Contents
- **Classical Approach:** Requires `n` queries to reveal each bit of `s`.  
- **Quantum Approach:** Uses superposition and interference to reveal all bits in **one query**.  
- **Implementation:** Qiskit circuit with oracle construction and measurement.  
- **Visualizations:** Circuit diagrams and histograms showing the recovered secret string.  

---

## 📂 Files
- `bernstein_vazirani.ipynb` → Jupyter Notebook with implementation and simulations.  
- `requirements.txt` → Dependencies for running the notebook.  
- `README.md` → This documentation file.  

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install qiskit matplotlib
