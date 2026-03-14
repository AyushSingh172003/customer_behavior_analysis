# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes **customer shopping behavior** using transactional retail data to uncover insights into purchasing patterns, customer segments, and product performance. The goal is to help businesses better understand their customers and make **data-driven decisions to improve sales, marketing strategies, and customer loyalty**.

The analysis combines **Python for data preparation, PostgreSQL for business analytics, and Power BI for interactive visualization**, creating a complete end-to-end data analytics workflow.

---

## Business Problem
A retail company wants to better understand how customers shop across demographics, product categories, and purchase channels. Management aims to identify which factors—such as discounts, product reviews, seasons, or customer purchase history—drive buying decisions and repeat purchases.

The key business question addressed in this project:

**How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

## Dataset Overview
The dataset contains customer purchase transaction records with information related to demographics, purchasing behavior, and product details.

**Dataset Highlights**

- Total Records: **3,900 transactions**
- Total Features: **18 columns**
- Customer data: Age, Gender, Location, Subscription Status
- Purchase details: Item Purchased, Category, Purchase Amount
- Behavioral data: Discount Applied, Previous Purchases, Frequency of Purchases
- Product feedback: Review Rating
- Logistics: Shipping Type

---

## Project Workflow

### 1. Data Preparation (Python)
Data preprocessing and exploration were performed using **Python and Pandas**.

Key steps included:
- Loading and exploring the dataset
- Handling missing values in review ratings
- Standardizing column names for consistency
- Creating additional features:
  - `age_group`
  - `purchase_frequency_days`
- Removing redundant columns
- Validating data consistency
- Loading the cleaned dataset into **PostgreSQL**

---

### 2. Data Analysis (SQL)
SQL queries were written in **PostgreSQL** to extract insights and answer key business questions.

Key analyses performed:

1. Revenue comparison by gender  
2. Customers who used discounts but spent above the average purchase amount  
3. Top 5 products with the highest average review rating  
4. Average purchase comparison by shipping type  
5. Spending behavior of subscribed vs non-subscribed customers  
6. Products with the highest percentage of discounted purchases  
7. Customer segmentation (New, Returning, Loyal)  
8. Top 3 most purchased products within each category  
9. Relationship between repeat buyers and subscription adoption  
10. Revenue contribution by age group

---

### 3. Data Visualization (Power BI)
An **interactive Power BI dashboard** was built to visualize insights and trends.

Dashboard highlights include:

- Customer distribution and subscription breakdown
- Revenue by product category
- Sales by category
- Revenue by age group
- Average purchase amount
- Product review ratings
- Dynamic filtering for better analysis

The dashboard enables stakeholders to explore patterns and better understand customer behavior.

---

## Key Insights
Some insights discovered from the analysis include:

- Certain products rely heavily on **discounts to drive purchases**
- **Loyal customers contribute significantly to revenue**
- Subscription status influences spending behavior
- Different **age groups show varying purchasing patterns**
- Certain product categories dominate total revenue

---

## Business Recommendations

Based on the analysis, the following recommendations were identified:

- Implement stronger **customer loyalty programs**
- Offer exclusive incentives for **subscribers**
- Optimize **discount strategies** to balance profitability and sales
- Highlight **top-rated and best-selling products** in campaigns
- Use **customer segmentation** for targeted marketing

---

## Project Deliverables

This repository contains:

- Python scripts for data preparation
- SQL queries for business analysis
- Power BI dashboard file
- Project report
- Gamma AI presentation (PPT)
- Business problem statement documentation

---

## Tech Stack

**Programming & Analysis**
- Python
- Pandas
- SQL (PostgreSQL)

**Visualization**
- Power BI

**Documentation**
- Gamma AI
- GitHub

---

## Repository Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv        # Raw dataset
├── Project1.ipynb                        # Python data cleaning and exploration
├── Sql Querries.sql                      # SQL queries used for business analysis
├── Customer Behavior Dashboard.pbix      # Power BI dashboard file
├── Customer Shopping Behavior Analysis Report.pdf   # Detailed project report
├── Customer-Shopping-Behavior-Analysis.pptx         # Gamma AI presentation
├── Business Problem Document.pdf         # Business problem statement
└── README.md                             # Project documentation
```

## Future Improvements

Possible enhancements for this project include:

- Predictive modeling for customer churn
- Customer lifetime value analysis
- Real-time sales dashboards
- Advanced cohort and retention analysis

---

## Author

**Ayush Singh**
