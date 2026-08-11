# 📊 Exploratory Data Analysis & Data Cleaning with Pandas

This repository contains an Exploratory Data Analysis (EDA) and a complete data cleaning pipeline implemented using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 🛠️ Tech Stack

* **Python 3.x**
* **Pandas:** Data loading, manipulation, and cleaning.
* **Matplotlib & Seaborn:** Data visualization and statistical plots.

---

## 📝 Workflow Overview

### 1. Initial Inspection & Data Loading
* Dataset ingestion via `pd.read_csv()`.
* Structural inspection and data type evaluation using `.info()` and `.head()`.

### 2. Data Cleaning & Preprocessing
* **Missing Values:** Identified and removed null records using proper DataFrame reassignment to ensure changes persist:
  ```python
  df = df.dropna()
