# Credit Card Data Analysis 💳

### Dashboard Link :https://app.powerbi.com/links/mIlCKQMpxu?ctid=37d002c9-062c-435d-beff-d1efc9989fe4&pbi_source=linkShare

## Problem Statement
Banks and financial institutions need a deeper understanding of customer credit card usage trends. By analyzing transaction data across time, gender, card type, and expenditure type, organizations can identify spending patterns, customer segments, and potential risk areas to improve decision-making.

## Key Objective

- Study yearly and monthly trends of transactions
- Build KPIs for total transactions by card type and gender
- Compare spending patterns across card types and demographics
- Provide actionable insights for financial decision-making


### Steps followed 

Step 1 – Data Loading

- Loaded card dataset from CSV File in into Power BI.

Step 2: Open Power Query Editor and in the View tab under Data Preview, enabled:

- Enabled:

  - Column distribution

  - Column quality

  - Column profile

- Set profiling to "Based on entire dataset".

Also, changed profiling to “Based on entire dataset”.

Step 3 – Data Quality Checks

- Checked for null values in Gender, City, Card Type.
- Date fields formatted properly to enable Year/Month slicers


Step 5 : Built visuals
Created card visuals with DAX measures:
- Column Chart → Transactions by Card Type & Gender
- Donut Chart → Total Transactions by Card Type
- Column Chart → Total Transactions by Gender
- Line Chart → Transactions over Year, Month, Gender


Step 5 – Slicers Added

- Time Period
- Gender
- Card Type
- Exp Type
- 3 Parameters

Step 8 - Publish to Power BI Service 
- Published dashboard for cloud access and sharing with stakeholders.


![Publish_Message](https://github.com/user-attachments/assets/ade68bec-ee73-469d-b699-7379f9c3d123)

# Dashboard :   Home Page 

![dashboard_snapo](https://github.com/user-attachments/assets/5ae2de41-1dae-4fd7-b88d-348833db4f26)

# Dashboard :   Transaction Page 

![dashboard_snapo](https://github.com/user-attachments/assets/0032f6c8-056c-43db-85d0-86f500946789)

 
# Insights

### Loan Portfolio Performance

- Spending by Card Type: Premium cards show higher average transactions compared to standard ones.

- Gender-Based Trends: Distinct differences in spending behavior between male and female customers.

- Time Series: Seasonal peaks observed in festive months and year-end periods.

- Expenditure Types: Certain categories (shopping, travel) dominate credit card usage.



# Conclusion

This dashboard enables a comprehensive analysis of credit card transaction patterns. By leveraging filters and visual insights, banks can segment customers, track card performance, and design targeted offers to improve customer satisfaction and revenue.


## Resources

[Card Dataset](https://drive.google.com/drive/folders/1jwFjanv9RnoeDvyFbOs4EKKx8VEXmYvi?usp=drive_link)


## Authors

- [1908Deepak](https://github.com/1908Deepak)


## Feedback

If you have any feedback, please reach out to us at deepaksingh190810@gmail.com

