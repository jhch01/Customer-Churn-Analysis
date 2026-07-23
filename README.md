# Customer-Churn-Analysis
## Project Overview
Customer retention is a major challenge for subscription-based businesses. This project analyzes customer churn patterns within a telecommunications company to identify the factors contributing to customer loss and determine which customer segments are at the highest risk of leaving. 

Using SQL and Tableau, I transformed raw customer data into actionable insights by analyzing customer demographics, contract information, service subscriptions, and customer value metrics. The goal of this project was to understand why customers churn and identify opportunities to improve retention strategies. 
## Tools Used
- SQL (BigQuery)
- Tableau
- GitHub
## Data Model
The original dataset contained: 
- Customer demographics
- Account information
- Service subscriptions
- Customer lifetime value (CLTV)
- Churn information
A reporting dataset was created in BigQuery and exported to Tableau for visualization.
## Business Questions
- What percentage of customers are leaving the company?
- Which customer segments have the highest churn rates?
- How do contract type, tenure, and payment method influence churn?
- Are additional services associated with better customer retention?
- Which customer groups should businesses prioritize for retention efforts? 
## Dashboard 1: Customer Churn Overview
![Customer Churn Overview](Tableau/Customer%20Churn%20Overview%20Dashboard.png)
Focus: 
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
Focus: 
- Customer status by gender
- Customer status by senior citizen
- Churn rate by partner
- Churn rate by charge group
## Dashboard 3: Service Analysis
![Service Analysis](Tableau/Service%20Analysis%20Dashboard.png)
Focus: 
- Churn rate by tech support
- Churn rate by online security
- Churn rate by online backup
- Churn rate by device protection
- Churn rate by streaming TV
- Churn rate by streaming movies
## Key Insights
1. **New Customers Are Most At Risk**
   - Customers with 0-12 months of tenure have the highest churn rate at **47.4%**.
2. **Contract Type Is a Major Churn Driver**
   - Month-to-month customers have the highest churn rate at **42.7%**.
3. **Payment Method Impacts Retention**
   - Electronic check customers have the highest payment-method churn rate at **45.3%**.
4. **Higher Charges Are Associated With Increased Churn**
   - High charge customers have a churn rate of **35.4%**.
5. **Additional Services Improve Retention**
   - Customers without Tech Support and Online Security have churn rates above **41%**.
## Recommendations 
- Create stronger onboarding programs for customers within their first year.
- Encourage month-to-month customers to transition into longer-term contracts.
- Review pricing strategies for customers with high monthly charges.
- Promote support and security services as retention benefits.
- Develop targeted retention campaigns for high-risk customer segments.
- Encourage customers using electronic checks to consider alternative payment methods. 
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
