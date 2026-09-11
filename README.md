# Employee Attrition & Risk Analysis

An end-to-end **Machine Learning and HR Analytics project** that analyzes employee attrition patterns and identifies factors associated with employee turnover.

The project combines **Exploratory Data Analysis, Data Preprocessing, Machine Learning, Business Insights, and an Interactive Risk Analysis App** to provide a practical view of employee attrition.

## 🚀 Live Application

👉 **[Open Employee Attrition & Risk Analysis App](https://hatchable.com/r/SDJCZKBK)**

The interactive application allows users to explore attrition insights and simulate employee risk scenarios based on important factors identified during the analysis.

---

## 📌 Problem Statement

Employee attrition can create significant challenges for organizations, including increased hiring costs, productivity loss, and workforce instability.

The objective of this project is to:

* Analyze employee attrition patterns
* Identify factors associated with employees leaving the organization
* Build Machine Learning models for attrition prediction
* Evaluate model performance using appropriate metrics
* Translate ML findings into meaningful HR/business insights
* Provide an interactive application for exploring employee risk

---

## 📊 Dataset

The project uses an **IBM HR Analytics Employee Attrition & Performance** dataset containing information about employees, including:

* Job role
* Department
* Business travel
* Job satisfaction
* Environment satisfaction
* Monthly income
* Years at company
* Overtime
* Marital status
* Total working years
* Number of companies worked
* And other employee-related attributes

**Dataset size:** 1,470 employees

**Target variable:** `Attrition`

* `Yes` → Employee left the organization
* `No` → Employee stayed

---

## 🔍 Exploratory Data Analysis

The analysis explored employee demographics, job characteristics, satisfaction levels, overtime, departments, and other factors related to attrition.

### Key Findings

* **Total Employees:** 1,470
* **Employees Who Left:** 237
* **Employees Who Stayed:** 1,233
* **Overall Attrition Rate:** 16.12%

### Important Insights

**Overtime and Attrition**

Employees working overtime showed a substantially higher attrition rate than employees who did not work overtime.

**Department**

The Sales department showed a higher attrition rate compared with R&D.

**Other Important Factors**

The analysis also identified factors such as:

* Business travel
* Job role
* Years at company
* Marital status
* Job satisfaction
* Environment satisfaction
* Number of companies previously worked at

as important signals associated with employee attrition.

---

## 🤖 Machine Learning

The project experimented with multiple classification models:

### Models Used

1. Logistic Regression
2. Random Forest
3. Tuned Random Forest

### Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

### Model Performance

| Model               |   Accuracy |  Precision | Recall | F1 Score |    ROC-AUC |
| ------------------- | ---------: | ---------: | -----: | -------: | ---------: |
| Logistic Regression |     71.77% |     31.63% | 65.96% |   42.76% |     69.42% |
| Random Forest       |     84.35% |     55.56% | 10.64% |   17.86% |     80.75% |
| Tuned Random Forest | **84.69%** | **60.00%** | 12.77% |   21.05% | **80.31%** |

The models demonstrate the trade-off between overall accuracy and the ability to identify employees who may leave.

---

## 🧠 Risk Analysis

The project also examined important risk signals identified through the Logistic Regression model.

Some of the strongest positive attrition signals included:

* Overtime
* Frequent business travel
* Certain job roles
* Longer time at the company
* Single marital status
* Number of companies previously worked at

These signals help provide a business-oriented interpretation of the ML results.

> **Note:** Risk signals indicate statistical associations in the dataset and should not be interpreted as proof that an individual employee will leave.

---

## 📈 Interactive Application

The project includes a web-based application that presents the analysis in an interactive format.

### Application Features

* HR analytics dashboard
* Attrition overview
* Department-level attrition analysis
* Overtime vs. attrition analysis
* Workforce insights
* ML model performance
* Top risk signals
* Interactive Employee Risk Simulator
* Project pipeline overview

### Technology Used

* HTML
* CSS
* JavaScript
* Machine Learning analysis with Python
* Scikit-learn
* Hatchable

👉 **[Try the Live Application](https://employee-attrition.hatchable.site)**

---

## 🛠️ Project Workflow

```text
Raw HR Dataset
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Categorical Encoding
       ↓
Train / Test Split
       ↓
Machine Learning Models
       ↓
Model Evaluation
       ↓
Risk Factor Analysis
       ↓
Interactive Web Application
```

---

## 📂 Project Structure

```text
Employee-Attrition-Risk-Analysis/
│
├── Employee_Attrition_Analysis.ipynb
├── HR_Data.csv
├── README.md
│
├── app/
│   ├── index.html
│   ├── styles.css
│   └── app.js
│
└── screenshots/
    ├── dashboard.png
    ├── risk-simulator.png
    └── model-performance.png
```

---

## 💻 Technologies

**Programming & Data Analysis**

* Python
* Pandas
* NumPy

**Machine Learning**

* Scikit-learn
* Logistic Regression
* Random Forest

**Visualization & Analytics**

* Matplotlib
* Seaborn
* Tableau

**Application**

* HTML
* CSS
* JavaScript
* Hatchable

**Tools**

* Jupyter Notebook
* GitHub

---

## 🎯 Business Value

This project demonstrates how HR data can be transformed into actionable insights using Machine Learning.

Organizations can use similar approaches to:

* Identify workforce attrition patterns
* Understand factors associated with employee turnover
* Support employee retention strategies
* Monitor high-risk workforce segments
* Combine analytics with interactive decision-support tools

The application is intended for **analysis and educational purposes** and should not be used as the sole basis for employment decisions.

---

## 👩‍💻 Author

**[Piyusha Dhende]**

Computer Engineering Student | Data Science & AI/ML Enthusiast

Interested in **Data Analytics, Machine Learning, Artificial Intelligence, and Business Applications of Data**.

---

## ⭐ Project Highlights

* End-to-end Machine Learning workflow
* HR-focused business analysis
* Multiple classification models
* Model evaluation using multiple metrics
* Feature/risk signal analysis
* Tableau analytics dashboard
* Interactive web application
* GitHub-ready project structure

If you found this project useful, consider giving the repository a ⭐.
