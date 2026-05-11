# 📞 Telecom Customer Churn: Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-orange.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green.svg)

## 📌 Project Overview
This project focuses on identifying the key factors that contribute to customer attrition in the telecommunications industry. By performing **Exploratory Data Analysis (EDA)** on a dataset of 7,043 customers, I uncovered specific behavioral patterns and service preferences that distinguish loyal customers from those likely to leave.

---

## 🔍 Key Business Insights
Based on the analysis performed in the `Telecom_Churn_Analysis.ipynb` notebook:

* **Contract Vulnerability:** Customers on **Month-to-month** contracts are at the highest risk, showing a significantly higher churn rate compared to long-term subscribers.
* **The Payment Method Gap:** There is a strong correlation between **Electronic Check** payments and churn, suggesting a need for more automated, seamless billing options.
* **Service Quality vs. Price:** **Fiber Optic** users churn more frequently than DSL users, indicating that while speed is a selling point, pricing or service stability may be an issue.
* **Tenure Trends:** Most churn occurs within the **first 6 months** of the customer lifecycle.

---

## 📊 Featured Visualization
> **Why I chose this:** This chart (Churn vs. Contract Type) is the "smoking gun" of the analysis. It clearly shows that flexibility (Month-to-Month) comes at the cost of high attrition.

![Churn vs Contract Type](churn_analysis_plot.png) 
<img width="862" height="473" alt="image" src="https://github.com/user-attachments/assets/07914cb4-c641-4f54-9044-64d4d2dc4185" />

---

## 🛠️ Tools & Libraries Used
- **Data Cleaning & Manipulation:** Python, Pandas
- **Visual Storytelling:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 🚀 Conclusions & Recommendations
To reduce churn, the business should:
1. **Incentivize long-term contracts** with small discounts or loyalty perks.
2. **Improve onboarding** for new customers in their first quarter to build brand loyalty early.
3. **Investigate Fiber Optic service issues** to ensure the premium price matches the customer experience.

