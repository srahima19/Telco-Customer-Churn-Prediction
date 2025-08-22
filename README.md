# 📊 Telco Customer Churn Prediction

This project analyzes customer churn data from a telecom company. The main goal is to **understand churn patterns** using Exploratory Data Analysis (EDA) and then build **Machine Learning models** to predict whether a customer is likely to churn.

---

## 🎯 Objectives

* Perform **data cleaning** and preprocessing.
* Explore customer churn patterns using **EDA & visualizations**.
* Train **classification models** (Logistic Regression, Random Forest, etc.) to predict churn.
* Compare model performance and interpret results.

---

## 📂 Dataset

* **Source:** [Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
* **Rows:** \~7043
* **Columns:** 21
* **Target variable:** `Churn` (Yes / No)

---

## 🧱 Project Workflow

### 🔹 Part 1 – Data Cleaning & Preparation

* Dropped irrelevant columns (e.g., `customerID`).
* Converted `TotalCharges` to numeric and handled missing values.
* Encoded categorical variables (One-Hot Encoding).
* Verified dataset structure and handled null values.

### 🔹 Part 2 – Exploratory Data Analysis (EDA)

Key business questions answered:

1. What is the **distribution of churn**?
2. How does churn vary by **contract type**?
3. How does churn vary by **internet service type**?
4. What is the **correlation between numerical features**?
5. How does churn vary by **senior citizen status**?
6. How does churn vary by **payment method**?
7. How does churn vary across **other customer groups (gender, tenure, etc.)**?

📊 **Visualizations Used:**

* Count plots
* Bar plots
* Correlation heatmap
* Grouped churn rate comparisons

### 🔹 Part 3 – Machine Learning

* **Models Used:** Logistic Regression, Random Forest
* **Metrics Evaluated:**

  * Accuracy
  * Precision, Recall, F1-score (Classification Report)
  * Confusion Matrix
  * ROC Curve & AUC

📌 **Results:**

* Logistic Regression: \~80% accuracy
* Random Forest: \~85% accuracy (better performance)

---

## 📈 Insights

* Customers with **month-to-month contracts** are far more likely to churn.
* **Electronic check** users have the highest churn rate compared to credit card/automatic payments.
* **Senior citizens** churn more often than younger customers.
* High **monthly charges** increase churn risk.
* Longer **tenure customers** are less likely to churn.

---

## 🛠️ Tools & Libraries

* Python 🐍
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

⭐ If you find this project useful, feel free to fork or star this repo!

---
