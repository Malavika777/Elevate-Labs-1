# Task 1: Data Cleaning and Preprocessing

## 📌 Objective
The goal of this task was to clean and prepare a raw dataset by handling missing values, duplicates, inconsistent formatting, and ensuring data consistency. Some initial exploratory data analysis (EDA) and basic visualizations were also performed.

---

## 🛠️ Tools Used
- Python (Pandas, Matplotlib/Seaborn)
- Jupyter Notebook
- Excel (optional checks)

---

## 🧹 Cleaning and Preprocessing Steps

### ✅ 1. Missing Values
- Identified missing values using `.isnull()` and `.info()`
- Handled nulls by:
  - Dropping rows with critical missing values
  - Filling missing entries using mode/mean where appropriate

### ✅ 2. Duplicates
- Removed duplicate rows using `.drop_duplicates()`

### ✅ 3. Droping Null values
-Ensuring to drop the null values that are not required
  -Irrelevant values are dropped if null

---

## 📊 Exploratory Data Analysis (EDA)

Performed basic EDA to understand data distribution:
- Plotted value counts for categorical variables
- Distribution plots for age and other numeric fields
- Correlation heatmap (if applicable)

---

## 📁 Deliverables

- ✅ Cleaned dataset (CSV file)
- ✅ Jupyter notebook with all steps and EDA
- ✅ This README summary

---

## 🚀 How to Run
1. Clone this repo
2. Open the notebook using Jupyter:
