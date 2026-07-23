# BinX AI & ML Internship — Week 1: Day 5 & Mini-Project

## Data Visualization & Integrated Mini-Notebook

This repository contains the Day 5 hands-on lab and the Week 1 Integrated Mini-Notebook project. It demonstrates the complete end-to-end data pipeline (`Data Ingestion` → `Data Cleaning` → `Numerical Processing` → `Exploratory Data Analysis & Visualization`) using Python, NumPy, Pandas, Matplotlib, and Seaborn.

---

## 🎯 Learning Objectives
* Construct publication-quality visualizations using Matplotlib and Seaborn, ensuring proper labeling (X/Y axes, titles, and legends).
* Implement multi-chart layouts using `plt.subplots()` for comparative exploratory analysis.
* Execute an end-to-end data processing and EDA workflow within a single, reproducible Jupyter Notebook.
* Interpret chart distributions, continuous feature correlations, and dataset outliers to inform downstream machine learning modeling decisions.

---

## 🧪 Mini-Project Pipeline & Tasks Covered

1. **Data Ingestion & Preprocessing:** Loaded raw tabular data into Pandas DataFrames, performed null-value remediation, and validated non-null column distributions.
2. **Feature Engineering & Numerical Analysis:** Utilized NumPy array operations to compute derived summary metrics and statistical distributions.
3. **Exploratory Data Analysis (EDA) Visualizations:** Produced a unified figure containing three distinct, fully labeled plots:
   * **Histogram (Distribution Analysis):** Visualized age demographics and feature density spread using Seaborn/Matplotlib.
   * **Scatter Plot (Bivariate Relationship):** Analyzed multi-variable correlation patterns (e.g., `Age` vs. `Fare`).
   * **Box Plot (Outlier Analysis):** Quantified interquartile ranges (IQR), medians, and isolated extreme values.
4. **Data Storytelling & Interpretation:** Documented key observational insights directly underneath each plot using structured Markdown cells.

---

## 🛠️ Tools & Technologies Used
* **Language:** Python 3.10+
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn
* **Environment:** Virtual Environment (`.venv`)
* **Workflow:** Jupyter Notebook / VS Code
* **Version Control:** Git & GitHub

---

## 🚀 How to Run

1. Activate your virtual environment:
   ```bash
   # Windows (Git Bash)
   source .venv/Scripts/activate