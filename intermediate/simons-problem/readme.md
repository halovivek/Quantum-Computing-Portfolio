# Simon’s Problem: Data & Visualization

## 📖 Overview
This project explores **Simon’s Problem**, comparing classical and quantum query complexities.  
It includes a dataset (`simons_data.csv`) and a plotting notebook (`simons_problem_plots.ipynb`) to visualize query counts and success rates under ideal and noisy quantum conditions.

---

## 🧩 Problem Setup
- **Function:** `f(x) = f(x ⊕ s)` where `s` is a hidden n‑bit string.  
- **Goal:** Find `s` efficiently.  
- **Classical Approach:** May require up to `2^(n-1)` queries.  
- **Quantum Approach:** Requires only `n` queries, showing exponential speedup.

---

## 📂 Files
- `data/simons_data.csv` → Dataset containing query counts and success rates.  
- `simons_problem_plots.ipynb` → Jupyter Notebook for visualizations.  
- `README.md` → This documentation file.  

---

## 📊 Dataset Columns
- `n` → Input size (number of bits).  
- `classical_avg_queries` → Average number of queries for classical approach.  
- `quantum_queries_ideal` → Number of queries for ideal quantum simulation.  
- `quantum_queries_noisy` → Number of queries for noisy quantum simulation.  
- `quantum_success_ideal` → Success rate under ideal quantum conditions.  
- `quantum_success_noisy` → Success rate under noisy quantum conditions.  

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas matplotlib
