# Bank Customer Churn Analysis

## Business Objective
The objective of this project is to analyze historical bank customer data to identify key behavioral patterns and drivers of customer churn.  
The insights help banks improve customer retention strategies, reduce revenue loss, and proactively engage high-risk customers.

## Dataset
- Source: Kaggle (BankChurners Dataset)
- Raw Data: BankChurners.csv
- Cleaned Data: Final_Bank_Customers_Data.csv

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Power BI
- Statistical Analysis (Correlation)

## Data Cleaning & Feature Engineering
- Removed irrelevant and ID-based columns
- Handled missing values and 'Unknown' categories
- Created numerical churn target variable
- Engineered Avg Transaction Value feature
- Renamed columns for business readability

## Churn Driver Analysis
Top churn drivers identified using correlation analysis:
- Total Transactions Count
- Total Revolving Balance
- Avg Credit Utilization
- Transaction Activity Change
- Customer Contact Count

## Dashboard Overview
The Power BI dashboard contains two pages:
1. **Overview** – High-level churn KPIs and summary
2. **Diagnostics** – Root cause analysis of churn drivers

## Key Insights
- Customers with low transaction activity show the highest churn
- High customer contact frequency strongly correlates with churn
- Estimated revenue loss due to churn: ~₹50 Lakhs

## Business Recommendations
- Early engagement campaigns for low-activity customers
- Improved service resolution for high-contact customers
- Proactive churn prevention strategies

## Future Scope
- Build a churn prediction model
- Add time-based trend analysis
- Integrate customer support text analysis
