# Telecom-Customer-Churn-Analysis
Project Overview
This project analyzes a telecommunications dataset to identify why customers leave the company (churn). By examining customer demographics, service usage, and contract details, this analysis reveals the primary drivers of churn and provides data-driven recommendations to improve customer retention.

Key Findings
The analysis uncovered several critical patterns that influence a customer's decision to stay or leave:

The Contract Factor: Customers on Month-to-month plans are significantly more likely to leave than those on long-term (one or two-year) contracts.

The "First Year" Risk: Churn is most frequent during the initial months of service. The longer a customer stays, the less likely they are to cancel.

Pricing Pressure: Customers who churned generally paid higher average monthly charges than those who remained loyal.

Internet Service Insight: Fiber Optic users show a higher tendency to leave compared to DSL users, suggesting a possible gap between the service's cost and its perceived value/reliability.

Payment Friction: Electronic check users churn at a much higher rate than customers using automated payment methods like credit cards or bank transfers.

Technologies Used
Python (Core Analysis)

Pandas (Data Manipulation)

Matplotlib & Seaborn (Data Visualization)

Jupyter Notebook (Development Environment)

Dataset Description

The dataset includes information about:

Demographics: Gender, age range, and if they have partners/dependents.

Services: Phone, multiple lines, internet (DSL, Fiber optic), online security, backup, protection, and streaming.

Account Info: Tenure, contract type, payment method, paperless billing, monthly charges, and total charges.

Churn: Whether the customer left within the last month.
Visualizations

The analysis includes various plots to represent the data, including:

Univariate Analysis: Distributions of tenure, monthly charges, and contract types.

Bivariate Analysis: Relationships between churn and features like Internet Service and Payment Methods.

Multivariate Analysis: Trends of monthly charges over time categorized by churn status.
