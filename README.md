# Statistical Analysis of ICICI Prudential Bluechip Mutual Fund

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Minitab](https://img.shields.io/badge/Minitab-FF6B0B?style=for-the-badge)
![Statistics](https://img.shields.io/badge/Statistics-Business%20Intelligence-blue)
![Finance](https://img.shields.io/badge/Finance-Mutual%20Funds-green)

## 📖 Project Overview

This project is a detailed statistical investigation conducted as part of my B.Sc. in Statistics. The goal was to understand the key factors influencing the Net Asset Value (NAV) of one of India's largest mutual funds, the **ICICI Prudential Bluechip Fund**. By employing **Multiple Linear Regression** analysis, this study quantifies the relationship between the NAV and various financial metrics.

## 🎯 Objectives

1. To identify and quantify the interrelationships between key mutual fund parameters
2. To develop a robust multiple linear regression model to predict the NAV
3. To test the significance of the model and its individual predictors
4. To check the validity of regression assumptions through residual plots

## ⚙️ Tech Stack & Tools

- **Programming Language:** R
- **Statistical Software:** Minitab
- **Libraries Used:** Base R (for `lm()`, `pairs()`, `cor()`, `plot()`)
- **Concepts:** Multiple Linear Regression, Correlation Analysis, Hypothesis Testing, ANOVA, Residual Diagnostics

## 📊 Data Source

Data extracted from monthly factsheets of ICICI Prudential Bluechip Fund (SEBI compliant). Variables analyzed:

- **Y (Response Variable):** `NAV` (Net Asset Value)
- **X1:** `AUM` (Assets Under Management)
- **X2:** `Expense_Ratio`
- **X3:** `SD` (Standard Deviation)
- **X4:** `Avg_PE` (Average Price-to-Earnings Ratio)
- **X5:** `Avg_PB` (Average Price-to-Book Ratio)
- **X6:** `Sharpe` (Sharpe Ratio)
- **X7:** `Beta`

## 🔍 Methodology & Key Steps

1. **Data Import & Preparation**
2. **Exploratory Data Analysis (EDA)** with scatter plots and correlation matrix
3. **Model Building** using multiple linear regression
4. **Model Diagnostics** with significance testing and residual analysis

## 📈 Key Findings

- **High Correlation:** Strong positive correlation (`0.944`) between `NAV` and `AUM`
- **Effective Predictive Model:** R-Squared = 98.1% (highly significant)
- **Significant Predictors:** All variables were significant predictors of NAV
- **Inverse Relationships:** `Expense_Ratio` and `Avg_PB` showed negative relationship with NAV

## 📝 Conclusion

The project successfully created a statistically significant model to predict the NAV. The analysis confirms that `AUM` is the most dominant positive influencer, while metrics like `Expense Ratio` and `Avg_PB` have a constraining effect.

## 👨‍💻 Author

**Omkar Kailas Jadhav**
- Bachelor of Science (B.Sc.) in Statistics (2021-2024)
- K.T.H.M. College, Nashik
- Savitribai Phule Pune University

---

## **Note:** 
- This project was completed under the guidance of **Prof. Ganesh S. Phad**, Department of Statistics, K.T.H.M. College, Nashik.
