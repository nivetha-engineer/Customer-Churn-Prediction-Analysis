# Customer-Churn-Prediction-Analysis
A Python-based Data Analysis and Machine Learning project that analyzes customer behavior and predicts customer churn using Logistic Regression.
---
## 📌 Project Overview

This project focuses on analyzing customer data to understand churn patterns and predict whether a customer is likely to leave the service.

The project includes:
- Data analysis using Pandas
- Data visualization using Matplotlib & Seaborn
- Feature scaling using StandardScaler
- Machine Learning using Logistic Regression
  
---

## 🚀 Features

- 📂 Load customer dataset
- 📊 Analyze customer information
- 🔍 Check missing values
- 📉 View churn distribution
- 💰 Calculate average monthly bill
- ☎ Find customer with highest support calls
- 👥 Analyze churned customer age
- ➕ Create new feature: `YearlyBill`
- 📈 Generate visualizations
- 🤖 Train Logistic Regression model
- 📉 Evaluate model accuracy

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

customer_churn.py  
customer.csv

---

## 📊 Dataset Columns

| Column Name | Description |
|---|---|
| CustomerID | Unique customer ID |
| Age | Customer age |
| MonthlyBill | Monthly subscription bill |
| ContractYears | Number of contract years |
| SupportCalls | Number of customer support calls |
| Churn | Customer churn status (0 = No, 1 = Yes) |

---

## 🧪 Analysis Performed

- Checked dataset shape and columns
- Identified missing values
- Counted churn vs non-churn customers
- Calculated average monthly bill
- Found customer with highest support calls
- Calculated average age of churned customers
- Created `YearlyBill` feature

---

## 📈 Data Visualization

### 🥧 Pie Chart
Shows:
- Churn customers
- Non-churn customers

### 📊 Histogram
Displays Monthly Bill distribution.

### 📦 Boxplot
Shows age distribution and outliers.

---

## 🤖 Machine Learning Model

### Model Used
- Logistic Regression

### Input Features
- Age
- MonthlyBill
- ContractYears
- SupportCalls

### Target Variable
- Churn

---

## 🧠 Machine Learning Workflow

### ✅ Train-Test Split
Dataset split into:
- 70% Training Data
- 30% Testing Data

### ✅ Feature Scaling
Used:
```python
StandardScaler()

✅ Model Training

LogisticRegression()

✅ Prediction

model.predict()

📉 Evaluation Metrics

✅ Accuracy Score

Measures model performance.

✅ Confusion Matrix

Shows:

True Positives
True Negatives
False Positives
False Negatives

▶️ How to Run

1️⃣ Install Required Libraries

pip install pandas matplotlib seaborn scikit-learn

2️⃣ Save Dataset

Create:

customer.csv

Author

Nive

⭐ Support

If you like this project, give it a ⭐ on GitHub!
