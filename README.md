# Employee Attrition Prediction

## 📌 Project Overview

Employee attrition is a major challenge for organizations because employee turnover can increase recruitment, training, and operational costs.

This project uses Machine Learning to predict whether an employee is likely to leave an organization based on factors such as job role, overtime, income, job satisfaction, work experience, business travel, and work-life balance.

The project also includes an interactive Streamlit web application for making employee attrition predictions.

---

## 🚀 Live Demo

👉 [Employee Attrition Prediction – Streamlit App](https://employee-attrition-prediction-o8jwlbrwyqzqcepsnxzb3b.streamlit.app/)

---

## 🎯 Objectives

- Analyze employee data and identify attrition patterns.
- Perform data preprocessing and exploratory data analysis.
- Build multiple classification models.
- Compare model performance.
- Handle class imbalance.
- Tune the Random Forest model using GridSearchCV.
- Identify important factors associated with employee attrition.
- Deploy the final model using Streamlit.

---

## 📊 Dataset

The project uses the IBM HR Analytics Employee Attrition dataset.

The dataset contains employee information including:

- Age
- Business Travel
- Department
- Distance From Home
- Education
- Job Role
- Job Level
- Job Satisfaction
- Monthly Income
- Overtime
- Performance Rating
- Total Working Years
- Work-Life Balance
- Years at Company
- Years in Current Role
- Years Since Last Promotion
- Years With Current Manager
- Attrition

The target variable is:

**Attrition**

- `0` → Employee stays
- `1` → Employee leaves

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Data Preprocessing
   ↓
Logistic Regression
   ↓
Decision Tree
   ↓
Random Forest
   ↓
Hyperparameter Tuning
   ↓
Model Evaluation
   ↓
Feature Importance
   ↓
Model Saving
   ↓
Streamlit Application
