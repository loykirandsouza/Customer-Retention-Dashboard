# Retention Power BI Project

## Project Overview

This project focuses on analyzing customer retention for a telecom company using Power BI. The goal is to identify key factors contributing to customer churn, visualize retention trends, and provide actionable insights for reducing churn rates.

## Dataset

The dataset used for this project contains information on customer demographics, service usage, account details, and churn status. Key columns include:

- **customerID**: Unique identifier for each customer
- **gender, SeniorCitizen, Partner, Dependents**: Demographic information
- **tenure**: Duration of the customer relationship
- **PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies**: Service usage details
- **Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges**: Account and billing information
- **numAdminTickets, numTechTickets**: Support ticket counts
- **Churn**: Indicator of whether the customer has churned

## Key Performance Indicators (KPIs)

- **Churn Rate**: Percentage of customers who have churned
- **Retention Rate**: Percentage of customers who are retained
- **Average Tenure of Churned vs. Retained Customers**
- **Total Revenue from Retained and Churned Customers**
- **Ticket Analysis**: Comparison of admin and tech support tickets for churned vs. retained customers

## Visualizations

1. **Churn Rate Card**: Displays the overall churn rate
2. **Total Revenue Card**: Shows the sum of total charges for churned and retained customers
3. **Customer Count by Contract Type**: Bar chart visualizing the distribution of customers by contract type
4. **Tenure Comparison**: Line chart comparing average tenure of churned vs. retained customers
5. **Ticket Analysis**: Scatter plot comparing numTechTickets and numAdminTickets for churned vs. retained customers
6. **Service Usage Breakdown**: Pie chart showing the percentage of customers using different services

## Dashboard Features

- Interactive filters for gender, contract type, and internet service
- Drill-through options to analyze individual customer profiles
- Dynamic tooltips with detailed information

## Methodology

1. **Data Cleaning and Preparation**: Handled missing values, formatted columns, and ensured data consistency
2. **Data Modeling**: Created relationships between tables and defined measures using DAX
3. **KPI Calculation**: Used DAX formulas to calculate churn rate, average tenure, and total revenue
4. **Visualization**: Built visual components and ensured alignment with project objectives

## Insights and Recommendations

- Customers with month-to-month contracts have the highest churn rate
- Higher numbers of tech support tickets are correlated with increased churn
- Customers using multiple services and long-term contracts show higher retention
- Reducing support issues and promoting long-term contracts can improve retention

## Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query

## How to Use the Power BI File

1. Open the `.pbix` file in Power BI Desktop
2. Use slicers to filter data based on demographics, services, and tenure
3. Hover over visual elements to view detailed tooltips
4. Explore different pages of the dashboard for comprehensive insights

## Author

Loy Kiran Dsouza



