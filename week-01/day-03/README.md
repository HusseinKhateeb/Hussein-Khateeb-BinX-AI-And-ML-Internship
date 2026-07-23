# BinX AI & ML Internship — Week 1: Day 3

## Numerical Computing with NumPy

This repository contains the Day 3 hands-on lab notebook focused on vectorization, array manipulation, and fundamental numerical operations using NumPy—the numerical backbone of the AI/ML stack.

---

## 🎯 Learning Objectives
* Create 1D and 2D NumPy arrays using various methods (`array`, `zeros`, `ones`, `arange`, `linspace`, `random`) and inspect structural attributes (`shape`, `dtype`, `ndim`)[cite: 3].
* Index and slice multi-dimensional arrays efficiently, including multi-axis indexing (`array[row, col]`)[cite: 3].
* Apply boolean masking to select and filter array elements based on specific logical conditions[cite: 3].
* Leverage vectorized operations and broadcasting rules to perform fast, element-wise computations without slow Python `for` loops[cite: 3].

---

## 🧪 Hands-On Lab Tasks Covered

1. **Array Creation & Inspection:** Created a 2D array of shape `(4, 4)` containing values 1–16, verifying its exact shape and data type[cite: 3].
2. **Indexing & Slicing:** Extracted specific sub-components (such as the 2nd column and last row) using multi-dimensional slicing syntax[cite: 3].
3. **Boolean Masking:** Computed the array's mean value and filtered all elements greater than the calculated mean[cite: 3].
4. **Broadcasting Drill:** Successfully added a 1D row array to every row of a 2D matrix using NumPy's broadcasting rules and verified the mathematical output[cite: 3].

---

## 🛠️ Tools & Technologies Used
* **Language:** Python 3.10+[cite: 3]
* **Library:** NumPy[cite: 3]
* **Environment:** Virtual Environment (`.venv`)[cite: 3]
* **Workflow:** Jupyter Notebook / VS Code[cite: 3]
* **Version Control:** Git & GitHub[cite: 3]

---

## 🚀 How to Run

1. Activate your virtual environment:
   ```bash
   # Windows (Git Bash)
   source .venv/Scripts/activate