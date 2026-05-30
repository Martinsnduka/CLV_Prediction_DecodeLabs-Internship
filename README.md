# Customer_Lifetime_Value_Prediction_Project
To open the notebook make use of **Git Dev** after clicking on the clv_notebook

## Business Overview

This project addresses a core revenue forecasting challenge by building a predictive model that estimates how much revenue a customer will generate over their entire relationship with the business.

## Business Objective

Predict the Customer Lifetime Value (CLV) of each customer, enabling the business to prioritise high-value customers, optimise marketing spend, and drive long-term profitability.

**Key business question this model answers:**

1. How much total revenue can the business expect from a given customer over their lifetime?
2. Which customers are the most valuable and worth investing in?

## Dataset
The dataset captures customer demographics, transaction history, and behavioural patterns across the following features:

1. **CustomerSegment** : A classification of customers based on purchasing behaviour, value, or engagement level (e.g., Premium, Regular, New Customer).
2. **PreferredPaymentMethod** : The payment option most frequently used by the customer, such as credit card, bank transfer, or digital wallet.
3. **CustomerTenure_Months** : The total number of months the customer has maintained a relationship with the business. Longer tenure typically signals loyalty and lower churn risk.
3. **Recency_Days** : The number of days since the customer's last purchase or interaction. Lower recency indicates an active, engaged customer.
5. **PurchaseFrequency** : The rate at which a customer makes purchases within a specific period. A key driver of CLV — more frequent buyers naturally generate more revenue.
6. **AvgOrderValue** : The average amount spent per transaction. Higher values directly inflate lifetime revenue projections.
7. **TotalRevenue** : The cumulative revenue generated from the customer over their entire relationship with the business.
8. **TotalItemsBought** : The total quantity of products purchased by the customer across all transactions.
9. **TotalReturns** : The total number of items returned by the customer. High return rates can reduce net CLV.
10. **FavouriteCategory** : The product category most frequently purchased or preferred by the customer.
11. **Region** : The geographical location where the customer resides or primarily conducts transactions.
12. **Target Variable — CLV (Customer Lifetime Value)** : The estimated total revenue a customer is expected to generate throughout their entire relationship with the business.

## Model Development
Two regression algorithms were trained and evaluated to identify the best-performing model for predicting CLV.

### Model Performance Summary
1.  Linear Regression : MSE= 461,407.57 , R^2= 0.6740 
2. Random Forest Regressor : MSE= 74,417.16 , R^2 =  0.9474 

### Selected Model: Random Forest Regressor

## Project Workflow
The following workflow was sequentially followed:

**Data Collection and understanding → Exploratory Data Analysis → Feature Engineering → Model Training & Comparison → Evaluation → Model Export**


## Key Takeaways

1. The **Random Forest Regressor** with an R² of **0.9474** gives the business a highly reliable tool for CLV prediction — nearly 95% of the variation in customer revenue is explained by the model.
2. **Linear Regression** underperformed significantly (R² of 0.674), confirming that the relationship between customer features and lifetime value is non-linear and requires a more flexible model.
3. Customers with high purchase frequency and high average order value consistently drive the largest CLV predictions — these are the customers the business should prioritise for retention and upsell efforts.

## Author

**Martins Nduka**
Data Analyst | Data Scientist

[![Gmail](https://img.shields.io/badge/Gmail-ndukamartins2019%40gmail.com-red?style=flat&logo=gmail)](mailto:ndukamartins2019@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-martins--nduka--122x-blue?style=flat&logo=linkedin)](https://linkedin.com/in/martins-nduka-122x)
