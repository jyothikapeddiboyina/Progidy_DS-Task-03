# 🧠 Decision Tree Classifier – Customer Purchase Prediction

## 📌 Project Overview
This project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product/service based on their demographic and behavioral data.

The dataset used is the **Bank Marketing Dataset**, which contains customer information such as age, job, marital status, balance, and previous interactions.

---

## 🎯 Objective
- To classify customers into:
  - ✅ **Will Purchase (Yes)**
  - ❌ **Will Not Purchase (No)**
- Use Machine Learning (Decision Tree) for prediction.

---

## 📂 Dataset
- Source: UCI Machine Learning Repository  
- GitHub Link:  
  👉 https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203

- Dataset Used:
  - `bank.csv`

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🪜 Steps Performed

### 1️⃣ Data Loading
- Loaded dataset using Pandas
- Fixed separator issue (`sep=';'`)

### 2️⃣ Data Preprocessing
- Converted categorical data into numerical using:
  ```python
  pd.get_dummies()
