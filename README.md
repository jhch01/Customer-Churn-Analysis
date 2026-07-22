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
- Sales Fact Table
- Customers Dimension
- Dates Dimension
- Products Dimension
A reporting dataset was created in BigQuery and exported to Tableau for visualization.
## Business Questions
- What percentage of customers are leaving the company?
- Which customer segments have the highest churn rates?
- How do contract type, tenure, and payment method influence churn?
- Are additional services associated with better customer retention?
- Which customer groups should businesses prioritize for retention efforts? 
## Dashboard 1: Customer Churn Overview
![Customer Churn Overview](Dashboard/Executive%20Overview%20Dashboard.png)
Focus: 
- Total Revenue
- Total Quantity Sold
- Monthly Revenue Trend
## Dashboard 2: Revenue Drivers
![Revenue Drivers](Dashboard/Revenue%20Drivers%20Dashboard.png)
Focus: 
- Revenue by Gender
- Revenue by Age Group
- Revenue by Weekday
## Dashboard 3: Product Performance
![Product Performance](Dashboard/Product%20Performance%20Dashboard.png)
Focus: 
- Revenue by Product Category
- Quantity Sold by Category
- Average Revenue per Transaction
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
- Increase marketing efforts toward customers aged 50+, the highest revenue-generating demographic.
- Maintain strong inventory levels for top-performing product categories, particularly Electronics.
- Align promotional campaigns with historically high-performing months such as May.
- Conduct further analysis on underperforming categories to identify pricing, inventory, or marketing opportunities.
## Tableau Dashboard 
View the interactive dashboard here: 
ADD LINK 
## Skills Demonstrated 
- SQL (Joins, Aggregations, CTEs)
- BigQuery
- Data Modeling
- Data Cleaning and Transformation
- Tableau Dashboard Development
- Business Intelligence Reporting
- Data Visualization
- Data Analysis and Insight Generation
