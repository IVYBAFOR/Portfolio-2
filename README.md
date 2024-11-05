# **Project 2: Customer Segmentation for a Subscription Service**

###  Project Overview
---
Objective: Analyze customer data for a subscription service to understand customer behavior, identify key trends in cancellations and renewals, and segment customers by subscription type and duration. The end goal is to deliver a Power BI dashboard that visualizes the insights.

### Data Source
---
The SalesData database is a collection of 50,000 records capturing transactional data for a retail store. Each record represents an individual order and contains information relevant to sales performance analysis. The database includes the following fields:
- CustomerID: A unique identifier for each customer, allowing tracking and segmentation of individual users.
- Region: The geographical location of the customer, useful for analyzing regional trends and preferences.
- SubscriptionType: The type of subscription each customer holds (e.g., Basic, Premium, Annual, Monthly), helping to identify the popularity of different subscription levels.
- StartDate: The date when the customer’s subscription began, allowing analysis of subscription longevity and retention.
- EndDate: The date when the subscription ended (or is blank if still active), which aids in tracking cancellations and active subscriptions.
- Revenue: The total revenue generated from each customer’s subscription, useful for calculating lifetime value and revenue by subscription type.

### Tools used
---

- Microsoft Excel
  1. For Data Cleaning
  2. For Analysis
  3. For Visualization

- SQL - Structured Query Language
- PowerBI
- Github

### Data Cleaning and preparation
---
Process used:
- In Excel, clean the data by removing duplicates, handling null values in key columns (e.g., Start Date, Subscription Type), and formatting dates.
- In SQL, load the data into a SQL Server environment for further analysis and validation.

Key Steps:
- Remove duplicates and format data types.
- Fill or drop rows with missing values in essential columns.
- Filter out records where the subscription data is inconsistent

### Exploratory Data Analysis
---
Excel Analysis:
- Use pivot tables to identify trends in subscription patterns by region and type.
- Calculate the average subscription duration and analyze which subscription types are the most popular.

### Data Analysis
---
![Annotation 2024-11-05 131303](https://github.com/user-attachments/assets/e54527bb-98c4-46d7-b8c5-ad87414d8513)

![Annotation 2024-11-05 131336](https://github.com/user-attachments/assets/71346305-e17a-43c5-8f6f-33723f186b7c)

### Data Visulaization 

### Recommendation
