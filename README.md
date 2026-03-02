# 📊 Bank Marketing Campaign Analysis

## 📌 Project Overview
This project analyzes a bank marketing campaign dataset to identify key factors influencing customer subscription to term deposits. The objective is to uncover demographic, financial, and campaign-related drivers of conversion using exploratory data analysis (EDA).

---

## 📈 Results Summary
The analysis identified call duration, previous campaign outcome, and specific demographic segments as the strongest drivers of term deposit subscription. These insights provide clear opportunities for improving campaign targeting and efficiency.

## 🎯 Business Problem
The bank conducted direct marketing campaigns to promote term deposits. The goal of this analysis is to determine:
- Which customer segments are most likely to subscribe
- Which campaign strategies improve conversion rates
- How engagement metrics influence outcomes

---

## 📂 Dataset Information
- Source: UCI Machine Learning Repository
- Observations: 41,188 customers
- Features: 21 variables
- Target Variable: `y` (Subscription: yes/no)

The dataset includes:
- Demographic attributes (age, job, marital status, education)
- Financial information (balance, housing loan, personal loan)
- Campaign-related details (duration, number of contacts, previous outcome)
- Economic indicators

---

## 🧹 Data Preparation
- Verified dataset dimensions and structure
- Checked for missing values and placeholder values (`"unknown"`)
- Created age groups for demographic segmentation
- Conducted exploratory feature validation

---

## 📊 Exploratory Data Analysis

### 🔹 Key Analyses Performed
- Target variable distribution
- Call duration vs subscription
- Previous campaign outcome vs subscription
- Age group and job multivariate segmentation
- Campaign contact frequency analysis
- Correlation heatmap of numerical variables

---

## 🔎 Key Insights

- 📞 Longer call durations significantly increase subscription likelihood.
- 🔁 Customers with previous successful campaign responses are more likely to convert again.
- 👥 Certain age group and job combinations show higher subscription rates.
- 📉 Excessive contact attempts may reduce conversion probability.
- 📊 Duration shows the strongest relationship with subscription among numerical variables.

---

## 🎯 Business Recommendations

- Prioritize customers with positive previous campaign outcomes.
- Focus marketing efforts on high-performing demographic segments.
- Improve call engagement strategies to increase conversation duration.
- Avoid excessive repeated contact attempts.
- Apply data-driven segmentation to improve campaign efficiency.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

---

## 📁 Project Structure

```
Data-Analysis-portfolio/
│
├── data/ # Raw dataset
├── notebooks/
│ └── analysis.ipynb # Full exploratory analysis
├── README.md
├── requirements.txt
└── .gitignore

```
---

## 🚀 Future Improvements
- Build predictive machine learning model
- Perform feature importance analysis
- Develop dashboard for business stakeholders