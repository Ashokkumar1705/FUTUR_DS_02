# Customer Retention & Churn Analysis
📌 Project Overview

Customer churn is a critical challenge for subscription-based businesses. Retaining existing customers is significantly more cost-effective than acquiring new ones.
This project analyzes customer data to identify churn patterns, key retention drivers, and customer lifetime trends, and translates insights into actionable business strategies.

🎯 Objectives

Identify customers most likely to churn

Understand when and why churn occurs

Analyze customer lifetime behavior

Provide data-driven recommendations to reduce customer loss

🗂️ Dataset Information

Records: 7,032 customers

Features Used: 16

Target Variable: Churn (Yes / No)

Key Features

Tenure

Contract Type

Monthly & Total Charges

Payment Method

Value-added Services (TechSupport, OnlineSecurity, etc.)

Customer Demographics

🛠️ Tools & Technologies

Python

Pandas – data cleaning & analysis

Seaborn / Matplotlib – visualization

Jupyter Notebook

🔍 Analysis Approach
1. Data Preparation

Converted TotalCharges to numeric format

Handled missing values

Encoded churn into binary format

Selected only retention-relevant features

2. Churn Overview

Calculated overall churn rate

Established baseline churn for comparison

3. Customer Lifetime & Retention Analysis

Analyzed churn behavior across customer tenure

Created tenure cohorts to identify early-stage churn patterns

Key Insight:
Churn is heavily concentrated within the first 6 months of the customer lifecycle.

4. Key Retention Drivers

Churn was analyzed across multiple dimensions:

Contract Type – Month-to-month customers churn significantly more

Pricing – Higher MonthlyCharges increase churn risk, especially for new users

Services – Lack of TechSupport and OnlineSecurity correlates with higher churn

Payment Method – Electronic Check users exhibit higher churn

5. High-Risk Customer Profile

A typical high-risk churn customer:

Has tenure < 6 months

Is on a month-to-month contract

Pays higher MonthlyCharges

Lacks TechSupport / OnlineSecurity

Uses Electronic Check as payment method

This profile enables targeted retention actions, not blanket discounts.

6. Customer Lifetime Value (CLV)

A simple lifetime metric was used:

Estimated CLV = MonthlyCharges × Tenure


Retained customers generate significantly higher lifetime value

Early churn directly results in lost long-term revenue

## 📈 Key Insights

Churn is primarily an early-lifecycle problem

Commitment and perceived value strongly influence retention

Support services play a critical role in reducing churn

Payment friction is a hidden but important churn factor

##  Business Recommendations
🎯 Retention Strategies

Early-Stage Retention Focus

Proactively engage customers within the first 6 months

Improve onboarding and early support

Contract Conversion Incentives

Encourage migration from month-to-month to long-term plans

Service Bundling Strategy

Bundle TechSupport and OnlineSecurity for new or high-risk customers

Price Sensitivity Management

Target high-charge, low-tenure users with retention pricing

Payment Method Optimization

Incentivize auto-pay methods to reduce churn risk

Each recommendation is directly tied to observed churn drivers.
## Conclusion

This project demonstrates how customer churn is driven by early tenure, low commitment, pricing pressure, lack of support services, and payment friction. By focusing on targeted retention strategies rather than blanket discounts, businesses can significantly reduce churn and increase customer lifetime value.

## Future Enhancements

Predictive churn modeling (Logistic Regression / Tree-based models)

Advanced cohort analysis

Integration with Power BI for interactive dashboards
