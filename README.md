# Employee Attrition Prediction & Risk Analysis

## 📌 Overview

This project combines HR Analytics and Machine Learning to analyze
employee attrition and identify employees who may be at risk of leaving.

The project uses Python and Scikit-learn for predictive modeling and
Tableau for interactive HR analytics.

## 🎯 Objectives

- Analyze employee attrition patterns
- Identify factors associated with employee turnover
- Build a machine learning model for attrition prediction
- Compare different classification models
- Generate business insights for HR decision-making

## 📊 Dataset

The dataset contains 1,470 employee records and 39 initial features.

Target variable:
- Attrition: Yes / No

## 🔧 Data Preprocessing

- Removed irrelevant and constant columns
- Checked missing values
- Encoded the target variable
- Applied one-hot encoding to categorical variables
- Performed an 80/20 stratified train-test split
- Applied feature scaling for Logistic Regression

## 🤖 Machine Learning Models

### Logistic Regression
Used as an interpretable baseline model.

### Random Forest
Used to capture nonlinear relationships between employee characteristics.

### Tuned Random Forest
Class weights were adjusted to give greater importance to the minority
attrition class.

## 📈 Model Results

| Model | Accuracy | Precision | Recall | F1 | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 71.77% | 31.63% | 65.96% | 42.76% | 69.42% |
| Random Forest | 84.35% | 55.56% | 10.64% | 17.86% | 80.75% |
| Tuned Random Forest | 84.69% | 60.00% | 12.77% | 21.05% | 80.31% |

## 🏆 Model Selection

Logistic Regression was selected as the primary attrition-detection model
because it achieved substantially higher recall and F1-score for the
minority attrition class.

Although Random Forest achieved higher accuracy and ROC-AUC, it missed
most employees who actually left.

## 📊 Tableau Dashboard

The Tableau dashboard provides interactive analysis of:

- Overall employee attrition
- Attrition rate
- Department
- Gender
- Age groups
- Job satisfaction
- Education field
- Overtime and attrition

![HR Analytics Dashboard](images/HR_Analytics_Dashboard.png)

## 💡 Business Value

The project demonstrates how organizations can combine descriptive HR
analytics with machine learning to better understand employee turnover
and identify potential attrition risks.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Tableau
- Jupyter Notebook
