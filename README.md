# CUSTOMERS CHURN ANALYSIS USING ANALYSIS
### Uncovering Drivers of Customer Retention and Reducing Churn through Data Insights

<img width="3000" height="2000" alt="image" src="https://github.com/user-attachments/assets/b00946e6-34d9-4980-b6fd-7e70362d256c" />

---

## Table of Contents
- Overview
- Business Problems
- Datasets
  - 1. Churn-Data
  - 2. Customers-Data
  - 3. Internet-Data
- Tools & Technologies
- Key Insights
- Final Recommendations
- Author & Contact
- Tags & Keywords

---

## Overview
This project analyzes telecom customer churn by integrating demographic data, contract attributes, billing methods, and internet service usage to identify the strongest drivers of churn and recommend targeted retention strategies. The analysis follows a structured Python workflow, including data cleaning, exploratory data analysis (EDA), and insight generation.

---

## Business Problems
- Identify at-risk customers to enable timely, proactive retention interventions.
- Understand the key behavioral and contractual factors influencing churn.
- Translate insights into practical, data-driven retention strategies to improve overall customer lifetime value.

---

## Datasets

The project uses three datasets that together provide customer demographics, internet services, and churn outcomes.

### 1. Churn-Data
This dataset contains the target variable (Churn) along with customer-level financial and contractual details.

Key fields include:
- CustomerID → Unique identifier for each customer.
- Tenure → Duration of the customer’s relationship with the company.
- Contract → Type of contract (Month-to-month, One-year, Two-year).
- PaperlessBilling → Indicates if the customer uses paperless billing.
- PaymentMethod → Method of payment (Electronic check, Bank transfer, Credit card, Mailed check).
- MonthlyCharges → Monthly bill amount paid by the customer.
- TotalCharges → Lifetime value spent by the customer.
- Churn → Target variable showing whether the customer left (Yes/No).

Files:
- CHURN_DATA.csv

### 2. Customers-Data
This dataset provides demographic and household-level attributes of customers.

Key fields include:
- Gender → Male/Female.
- SeniorCitizen → Whether the customer is a senior citizen (1/0).
- Partner → If the customer has a partner.
- Dependents → If the customer has dependents (children/parents).
- PhoneService → If the customer subscribed to phone service.
- MultipleLines → Whether multiple lines were used.

Files:
- CUSTOMER_DATA.csv

### 3. Internet-Data
This dataset covers internet service preferences and add-on services.

Key fields include:
- InternetService → Type of service (DSL, Fiber optic, None).
- OnlineSecurity → Whether the customer subscribed to online security.
- OnlineBackup → Availability of online backup service.
- DeviceProtection → Device protection subscription.
- TechSupport → Technical support availability.
- StreamingTV → Access to streaming TV.
- StreamingMovies → Access to streaming movies.

Files:
- INTERNET_DATA.csv

Data Dictionary:
- Telecom-Churn-Data-Dictionary.csv

Together, these datasets allow for a 360° analysis of churn behavior, covering demographics, contract terms, internet usage, and payment behavior.

---

## Tools & Technologies
- Languages: Python
- Environment: Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn
- Assets: Customer-Churn-Analysis-with-Python.pdf (slide/report)

---

## Key Insights
- Overall churn is approximately 26–27%, indicating roughly three-quarters of customers are retained.
- Month-to-month contracts exhibit the highest churn; one-year and two-year contracts show significantly lower churn.
- Churners pay higher MonthlyCharges on average; high charge + short tenure is a high-risk combination.
- Electronic check users churn the most; auto-pay methods (bank transfer/credit card) correlate with lower churn.
- Customers lacking OnlineSecurity or TechSupport have notably higher churn; bundling these add-ons reduces risk.
- Fiber optic users have higher churn than DSL or non-internet users, indicating segment-specific retention needs.
- Demographics like Gender show minimal difference in churn, suggesting service and contract factors dominate.

---

## Final Recommendations
- Promote longer-term contracts: Offer incentives to convert month-to-month users to one- or two-year plans.
- Focus on early-tenure journeys: Prioritize onboarding, proactive check-ins, and usage nudges within the first 12–18 months.
- Bundle value-added services: Cross-sell OnlineSecurity and TechSupport; these correlate with lower churn.
- Incentivize auto-pay: Provide small discounts or loyalty credits to shift electronic check users to auto-pay.
- Segment-specific care: Prioritize proactive support and save offers for fiber optic users and customers without dependents/partners.
- Monitor KPIs routinely: Track churn rate by tenure, contract type, payment method, and add-on adoption; set alerts for spikes.

---

## Author & Contact
Bhaskar Pal  
Aspiring Data Analyst

📧 Email: bhaskarpal.official@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/bhaskar-pal-2k02/  
🔗 Portfolio: https://bhaskarpal1707.github.io/portfolio/

---

## Tags & Keywords
Customer Churn, Telecom Analytics, Retention Strategy, Python, EDA, Data Visualization, Contract Analysis, Payment Behavior, Customer Segmentation, Business Intelligence, Machine Learning, Churn Reduction
