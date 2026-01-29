# TELCOM-CUSTOMER-CHURN-AND-REVENUE-ANALYSIS
# Telecom Customer Churn and Revenue Analysis

## Project Overview
The telecommunications industry is highly competitive, where retaining existing customers is more cost-effective than acquiring new ones. Customer churn — when a customer leaves a service provider — directly affects revenue and long-term growth. This project analyzes telecom customer data to understand revenue patterns and identify factors influencing churn.

Using data cleaning, feature engineering, exploratory data analysis (EDA), SQL queries, and Tableau visualizations, this project uncovers actionable insights to help reduce churn, optimize revenue, and improve customer retention strategies.

---

## Business Problem
The telecom company faces customer churn that negatively impacts revenue and profitability. Despite having access to extensive customer data, the company lacks a clear understanding of which factors influence churn and which customers are most valuable. Without this insight, retention strategies are based on assumptions rather than data.

---

## Problem Statement
This project aims to analyze telecom customer data to uncover revenue patterns and factors associated with customer churn. The analysis includes data cleaning, feature engineering, exploratory data analysis, SQL queries for business questions, and an interactive Tableau dashboard to support data-driven decision-making.

---

## Dataset Description
The dataset contains historical data for telecom customers, including:

- **Customer Information:** gender, senior citizen status, partner, dependents  
- **Services Subscribed:** phone, internet, streaming, tech support  
- **Account Details:** tenure, contract type, paperless billing, payment method  
- **Billing Information:** MonthlyCharges, TotalCharges  
- **Engineered Features:** TenureGroup, CustomerValue (Low / Mid / High), LogTotalCharges  

Target variable:  
- **Churn:** Indicates whether a customer left the company (Yes/No or 1/0)

---

## Project Workflow

1. **Data Cleaning**
   - Converted TotalCharges to numeric  
   - Handled missing values  
   - Encoded categorical variables  
   - Created engineered features: TenureGroup, CustomerValue, LogTotalCharges  

2. **Feature Engineering**
   - Grouped customers by tenure  
   - Categorized customers by total charges (low, mid, high value)  
   - Applied log transformation to revenue for better visualization  

3. **Exploratory Data Analysis (EDA)**
   - Analyzed churn distribution and revenue patterns  
   - Explored relationships between tenure, monthly charges, services, and churn  
   - Visualized customer segments and high-risk groups  

4. **SQL Analysis**
   - Calculated churn rate, average revenue by churn, top-value customers  
   - Identified high-risk churn customers based on contract type, tenure, and revenue  

5. **Tableau Dashboard**
   - Interactive dashboard showing KPIs, churn trends, revenue by tenure, customer value segments, and service-related churn  
   - Filters for contract type, internet service, tenure group, and churn status  
   - Business insights included for decision-making 
    

---

## Key Insights
- Customers on month-to-month contracts with shorter tenure are most likely to churn  
- Higher monthly charges are associated with increased churn  
- Long-term customers contribute significantly more to total revenue  
- High-value customers have lower churn rates but represent high revenue risk if they leave  
- Certain internet and service types are linked with higher churn  

---

## Business Recommendations
- Focus retention efforts on month-to-month customers, especially early in their tenure  
- Consider pricing adjustments or incentives for high monthly charges  
- Target high-value customers with loyalty programs to minimize revenue loss  
- Improve service quality for internet and streaming offerings with high churn  

---

## Tools and Technologies Used
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **SQL:** SQLite for querying and analysis  
- **Tableau:** Interactive dashboard creation for visual storytelling  

---

## Project Outcome
This project provides a **complete end-to-end analysis**, from raw data cleaning to actionable business recommendations and an interactive Tableau dashboard. It demonstrates strong **analytical thinking, data visualization skills, and business acumen**, making it a portfolio-ready project for data analyst or business intelligence roles.

---

## Repository Structure

