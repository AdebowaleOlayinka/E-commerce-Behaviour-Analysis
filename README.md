# E-commerce Customer Behaviour Analysis

## Tables of Content

- [Project Overview](#project-overview)
- [Data Set Overview](#data-set-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Tools and Techniques](#tools-and-techniques)

### Project Overview
This project aims to analyze customer behaviour and purchase history based on sales,return and payment preferences. It also analyze customer churn prediction, return rate, highest sold product category and revenue generated.The goal is to derive insight that can guide customer retention and enhance overall business perfomance.

### Data Set Overview
The data set used for the analysis is the E-commerce customer data Csv file, containing 250,000 rows and 14 columns
#### Column key field
- Customer ID
- Product Price
- Quantity
- Total Purchase Amount
- Payment Method
- Returns(0 for no return, 1 for return)
- Churn(0 for retained,1 for churned)
  
![Screenshot 2025-04-16 122347](https://github.com/user-attachments/assets/846b1624-e5aa-4503-8233-c4edf616c279)

### Exploratory Data Analysis
The exploratory data analysis aims to explore the data set to address key questions such as:
- Who are the top customers and how much do they contribute to revenue?
- Which category are experiencing the mnost returned order?
- Which product category are driving the most revenue?
- What age group are churning the most?
- What does our gender distribution tell us about our customer base?
- Which payment method do customer prefer?

## Tools and Techniques
- Microsoft Excel- Data Cleaning
- PowerBI- Data Visualization
  #### Techiques
- Data Cleaning: Microsoft Excel was used to remove duplicate and handling missing data
- The customer age was grouped using the IFS function in excel, the function state
  ### "IFS(H2<=25,"18-25",H2<=35,"26-35",H2>50,"50+")
  
