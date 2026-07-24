# Customer-Churn-Analysis
## Project Overview
Customer retention is a major challenge for subscription-based businesses. This project analyzes customer churn patterns within a telecommunications company to identify the factors contributing to customer loss and determine which customer segments are at the highest risk of leaving. 

Using SQL and Tableau, I transformed raw customer data into actionable insights by analyzing customer demographics, contract information, service subscriptions, and customer value metrics. The goal of this project was to understand why customers churn and identify opportunities to improve retention strategies. 
## Tools Used
- SQL (Google BigQuery)
- Tableau
- GitHub
**Dataset**

**Source:** Telco Customer Churn Dataset (Kaggle)

https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset/data

The dataset contains customer demographics, account information, subscribed services, customer lifetime value (CLTV), and churn information. The data was transformed using SQL in Google Bigquery before being visualized in Tableau.
## Data Model
The original dataset contained: 
- Customer demographics
- Account information
- Service subscriptions
- Customer lifetime value (CLTV)
- Churn information

A reporting dataset was created in Google BigQuery using SQL and connected to Tableau for interactive dashboard development.
## Business Questions
- What percentage of customers are leaving the company?
- Which customer segments have the highest churn rates?
- How do contract type, tenure, and payment method influence churn?
- Are additional services associated with better customer retention?
- Which customer groups should businesses prioritize for retention efforts? 
## Dashboard 1: Customer Churn Overview
![Customer Churn Overview](Tableau/Customer%20Churn%20Overview%20Dashboard.png)
**Focus Areas**
- Total customers
- Churned customers
- Churn rate
- Average CLTV
- Churn rate by contract
- Churn rate by internet service
- Churn rate by payment method
- Churn rate by tenure group
## Dashboard 2: Customer Segments
![Customer Segments](Tableau/Customer%20Segments%20Dashboard.png)
**Focus Areas**
- Customer status by gender
- Customer status by senior citizen
- Churn rate by partner
- Churn rate by charge group
## Dashboard 3: Service Analysis
![Service Analysis](Tableau/Service%20Analysis%20Dashboard.png)
**Focus Areas**
- Churn rate by tech support
- Churn rate by online security
- Churn rate by online backup
- Churn rate by device protection
- Churn rate by streaming TV
- Churn rate by streaming movies
## Key Insights
1. **New Customers Have the Highest Churn Risk**
   - Customers with **0-12 months of tenure** had the highest churn rate at **47.4%**, indicating the first year is the most critical period for customer retention.
2. **Contract Type Is Strongly Associated With Churn**
   - Customers on **month-to-month contracts** had the highest churn rate at **42.7%**, significantly higher than customers on longer-term contracts.
3. **Payment Method Is Associated With Higher Churn**
   - Customers using **electronic check** had the highest churn rate among payment-methods at **45.3%**.
4. **Higher Monthly Charges Are Linked to Increased Churn**
   - Customers in the **high charge group** experienced the highest churn rate at **35.4%**, suggesting pricing may influence customer retention.
5. **Support and Security Services Are Associated With Lower Churn**
   - Customers without **Tech Support (41.6%)** and **Online Security (41.8%)** experienced substantially higher churn rates than customers who subscribed to these services.
## Recommendations 
- Strengthen onboarding and engagement initiatives for customers during their first year.
- Encourage customers on month-to-month contracts to transition to longer-term plans.
- Evaluate pricing strategies and retention offers for customers with higher monthly charges.
- Increase awareness and adoption of support and security services to improve customer engagement.
- Develop targeted retention campaigns for customer segments with the highest churn risk.
- Monitor customers using electronic check payments and consider incentives to encourage alternative payment methods. 
## Tableau Dashboard 
View the interactive dashboard here: 
ADD LINK 
## Skills Demonstrated 
**SQL**
- Data cleaning and transformation
- Data aggregation
- Customer segmentation
- Creating analysis-ready datasets
- Business metric calculations
**Tableau**
- Dashboard development
- KPI creation
- Data visualization
- Business storytelling
- Translating analysis into insights
**Data Analysis**
- Customer churn analysis
- Retention analysis
- Identifying business drivers
- Developing actionable recommendations
