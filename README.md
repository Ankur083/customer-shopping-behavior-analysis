# Customer Shopping Behavior Analysis

An end-to-end data analytics project that analyzes customer shopping behavior to identify purchasing patterns, customer segments, product preferences, and factors influencing sales and customer loyalty.

## Project Overview

This project analyzes a retail customer dataset containing 3,900 purchase records and 18 columns.

The analysis focuses on answering business questions related to:

- Customer spending patterns
- Customer segmentation and loyalty
- Product performance
- Discount behavior
- Subscription behavior
- Shipping preferences
- Revenue contribution across age groups
- Repeat purchasing behavior

The project follows a complete analytics workflow:

**Python → PostgreSQL/SQL → Power BI → Business Insights**

## Business Objective

The main objective is to analyze consumer shopping data and generate insights that can help businesses:

- Improve customer engagement
- Understand purchasing behavior
- Optimize marketing strategies
- Improve customer retention
- Identify high-value customer segments
- Improve product positioning

## Dataset

The dataset contains:

- **3,900** purchase records
- **18** columns
- Customer demographic information
- Product and purchase information
- Shopping behavior information

### Important Features

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Frequency of Purchases

There were **37 missing values in the Review Rating column**, which were handled during data preparation.

## Technologies Used

### Python
- Pandas
- NumPy
- Jupyter Notebook

### SQL
- PostgreSQL
- SQL queries
- Aggregations
- Joins
- CASE statements
- Customer segmentation

### Visualization
- Microsoft Power BI

### Tools
- Git
- GitHub

## Project Workflow

### 1. Data Preparation using Python

The raw dataset was prepared using Python.

Tasks performed:

- Loaded the dataset using Pandas
- Explored the dataset using `info()` and `describe()`
- Checked missing values
- Imputed missing Review Rating values using the median rating of each product category
- Standardized column names using snake_case
- Created age groups
- Created purchase frequency features
- Checked data consistency
- Removed redundant information where appropriate
- Loaded the cleaned dataset into PostgreSQL

## 2. SQL Analysis

SQL was used to answer business-related questions from the cleaned dataset.

Analysis included:

- Revenue by gender
- High-spending customers using discounts
- Top-rated products
- Shipping type comparison
- Subscribers vs. non-subscribers
- Discount-dependent products
- Customer segmentation
- Top products by category
- Repeat buyers and subscription behavior
- Revenue by age group

## 3. Power BI Dashboard

An interactive Power BI dashboard was created to visualize the analyzed data.

The dashboard includes:

- Total customers
- Average purchase amount
- Average review rating
- Revenue by category
- Sales by category
- Subscription status
- Revenue by age group
- Sales by age group
- Shipping preferences
- Customer segmentation

## Key Business Insights

The analysis provides insights into:

- Customer spending behavior across different demographic groups
- Products receiving higher customer ratings
- The relationship between discounts and purchasing behavior
- Differences between subscribers and non-subscribers
- Customer loyalty and repeat purchasing patterns
- Product performance across categories
- Revenue contribution across different age groups
- Shipping preferences and their relationship with purchase amounts

## Business Recommendations

Based on the analysis, the project proposes:

### 1. Increase Subscription Adoption
Promote exclusive benefits and incentives to encourage customers to subscribe.

### 2. Strengthen Loyalty Programs
Reward repeat customers to improve retention and encourage movement toward loyal customer segments.

### 3. Improve Discount Strategy
Identify products and customer segments that respond strongly to discounts while maintaining healthy margins.

### 4. Improve Product Positioning
Use highly rated and frequently purchased products in marketing campaigns.

### 5. Targeted Marketing
Focus marketing efforts on high-value customer segments and relevant demographic groups.

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── customer_shopping_behavior.csv
├── Customer Shopping Behavior Analysis.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
├── Business Problem Document.pdf
├── LICENSE
└── README.md