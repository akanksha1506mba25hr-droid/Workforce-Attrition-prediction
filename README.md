# Workforce Attrition Prediction and Insights

## Overview

This project focuses on predicting employee attrition using machine learning and presenting the results through an interactive Power BI dashboard.

The solution enables HR teams to identify employees at risk of leaving, understand the key drivers behind attrition, and take proactive decisions to improve employee retention.

---

## Problem Statement

Employee attrition is a major challenge for organizations. HR teams often struggle to identify which employees are likely to leave due to multiple influencing factors such as salary, overtime, job role, and work-life balance.

This project addresses the problem by:

* Predicting attrition probability for each employee
* Categorizing employees into risk groups
* Providing explainability using SHAP values
* Delivering insights through a business-friendly dashboard

---

## Objectives

* Build a machine learning model to predict employee attrition
* Identify high-risk employees
* Analyze key factors influencing attrition
* Develop an interactive dashboard for decision-making

---

## Dataset

The dataset contains employee-level information including:

* Demographics (Age, Gender, Marital Status)
* Job Information (Department, Job Role, Job Level)
* Compensation (Monthly Income, Salary Hike)
* Work Conditions (Overtime, Work-Life Balance)
* Performance Metrics

The dataset is preprocessed and transformed into a business-friendly format for dashboard consumption.

---

## Methodology

### Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature selection

### Model Development

* Logistic Regression
* Random Forest
* Gradient Boosting / XGBoost

### Evaluation

* Accuracy
* Precision and Recall
* ROC-AUC

### Explainable AI

* SHAP values used to interpret model predictions
* Feature importance analysis
* This improves trust in AI predictions by making the model transparent and interpretable for HR decision-makers

### Dashboard Development

* Power BI used for visualization
* Interactive filters and drill-down analysis

---

## Dashboard Features

### Key Metrics

* Total Employees
* Actual Attrition Count
* Predicted Attrition Count
* Average Attrition Probability

### Visual Analysis

* Risk Category Distribution (High, Medium, Low)
* Attrition by Department
* Attrition by Job Role
* Overtime Impact on Attrition
* Salary vs Attrition Probability

### Interactivity

* Filters for Department, Job Role, and Risk Category
* Dynamic insights based on selection

---

## Dashboard Preview

<img width="1519" height="800" alt="Screenshot 2026-04-10 155146" src="https://github.com/user-attachments/assets/9bd1f5a7-d84d-4078-9234-309bdd4f3281" />


---


## Key Insights

* Employees working overtime show higher attrition risk
* Lower salary is strongly associated with higher attrition probability
* Certain departments (such as Sales) exhibit higher predicted attrition
* Majority of employees fall into the low-risk category

---

## Business Impact

This solution enables HR teams to reduce employee turnover by identifying high-risk employees early and taking proactive retention actions.

---

## Future Enhancements

* Real-time data integration
* Deployment as a web application
* Automated alerts for high-risk employees
* Integration with HR management systems

---

## Conclusion

This project demonstrates how machine learning and business intelligence tools can be combined to solve real-world HR problems. By integrating predictive analytics with explainable AI, the solution provides both accuracy and transparency for better decision-making.

---

## Author

Akanksha
