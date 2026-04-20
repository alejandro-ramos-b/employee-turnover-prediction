# Employee Turnover Prediction

## 📌 Project Overview

This project focuses on predicting employee turnover using machine learning techniques. The goal is to identify employees who are likely to leave the company and provide insights that can support retention strategies.

Employee turnover is a critical business problem, as losing skilled employees can impact productivity, increase hiring costs, and affect team performance.

---

## 🎯 Objectives

- Perform data quality checks and exploratory data analysis (EDA)
- Identify key factors influencing employee turnover
- Handle class imbalance using SMOTE
- Train and evaluate multiple machine learning models
- Compare model performance using appropriate metrics
- Develop actionable retention strategies based on predictions

---

## 📊 Dataset

The dataset includes information about employees such as:

- Satisfaction level  
- Last evaluation score  
- Number of projects  
- Average monthly hours  
- Time spent in the company  
- Work accidents  
- Promotion history  
- Department  
- Salary  

Target variable:
- **left** → 1 (employee left), 0 (employee stayed)

---

## 🔍 Exploratory Data Analysis (EDA)

- Analyzed correlations between numerical features  
- Visualized distributions of key variables such as satisfaction, evaluation, and working hours  
- Identified patterns related to employee turnover  
- Observed that satisfaction level and time spent in the company are strong indicators of attrition  

---

## 🧠 Clustering Analysis

- Applied K-Means clustering on employees who left  
- Identified different groups of employees based on satisfaction and evaluation  
- Observed that turnover occurs across multiple patterns, not only low satisfaction  

---

## ⚙️ Data Preprocessing

- Converted categorical variables using one-hot encoding  
- Split dataset into training and testing sets (80/20)  
- Applied SMOTE to handle class imbalance  

---

## 🤖 Models Used

- Logistic Regression  
- Random Forest Classifier  
- Gradient Boosting Classifier  

---

## 📈 Model Evaluation

Models were evaluated using:

- F1-score  
- Precision and Recall  
- ROC/AUC  
- Confusion Matrix  

The **Random Forest model** achieved the best performance across metrics.

---

## ⚖️ Key Insight on Evaluation

Recall was prioritized over precision because:

> Missing employees who are likely to leave (false negatives) can result in loss of valuable talent.

---

## 📊 Feature Importance

The most influential features were:

- Satisfaction level  
- Time spent in the company  
- Number of projects  
- Average monthly hours  

---

## 🧩 Retention Strategy

Employees were categorized into risk zones based on predicted probability:

- **Safe Zone (<20%)** → No immediate action required  
- **Low Risk (20–60%)** → Monitor and engage  
- **Medium Risk (60–90%)** → Apply retention strategies  
- **High Risk (>90%)** → Immediate intervention  

Suggested actions include:

- Workload adjustments  
- Career development opportunities  
- Recognition and feedback  
- Compensation review  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Imbalanced-learn (SMOTE)  

---

## 🚀 Conclusion

This project demonstrates how machine learning can be used to predict employee turnover and support data-driven decision-making.

By identifying high-risk employees and understanding key drivers of attrition, organizations can take proactive steps to improve retention and reduce costs.

---

## 📎 Author

**Alejandro Ramos Bojorquez**  
[GitHub](https://github.com/alejandro-ramos-b)
