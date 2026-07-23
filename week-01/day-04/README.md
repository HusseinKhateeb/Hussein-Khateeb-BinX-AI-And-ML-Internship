# BinX AI & ML Internship — Week 1: Day 4

## Tabular Data Analysis with Pandas

This repository contains the Day 4 hands-on lab notebook focused on loading, inspecting, filtering, cleaning, and aggregating tabular datasets using Pandas—the core data manipulation library in Python.

---

## 🎯 Learning Objectives
* Understand the core differences between Pandas `Series` (1D labeled arrays) and `DataFrames` (2D tabular structures).
* Load real-world CSV datasets and perform initial structural inspections using `.head()`, `.info()`, `.describe()`, and `.shape`.
* Perform targeted row filtering and column selection using label-based (`.loc`) and integer-based (`.iloc`) indexing.
* Clean raw datasets by identifying and handling missing values (`.fillna()`, `.dropna()`) and duplicate entries (`.drop_duplicates()`) with clear rationale.
* Execute "split-apply-combine" data aggregation routines using `.groupby()` and summary statistics.

---

## 🧪 Hands-On Lab Tasks Covered

1. **Dataset Ingestion & Inspection:** Loaded a CSV dataset into a Pandas DataFrame and analyzed its shape, column labels, non-null counts, and data types.
2. **Data Cleaning & Preprocessing:** Evaluated missing value counts across all features and handled them appropriately with documented justifications.
3. **Filtering & Subset Selection:** Applied conditional boolean filtering to isolate key subsets of the data and analyzed patterns within those ranges.
4. **Group Aggregation:** Utilized `.groupby()` and aggregate function mapping to calculate grouped statistics across categories and interpreted findings in Markdown cells.

---

## 🛠️ Tools & Technologies Used
* **Language:** Python 3.10+
* **Library:** Pandas
* **Environment:** Virtual Environment (`.venv`)
* **Workflow:** Jupyter Notebook / VS Code
* **Version Control:** Git & GitHub

---

## 🚀 How to Run

1. Activate your virtual environment:
   ```bash
   # Windows (Git Bash)
   source .venv/Scripts/activate