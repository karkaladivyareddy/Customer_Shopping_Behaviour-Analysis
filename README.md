# Customer_Shopping_Behaviour_Analysis

## Project Overview

This project analyses customer shopping behaviour using transactional
data from **3,900 purchases** across multiple product categories.\
The objective is to uncover insights into customer spending patterns,
segmentation, product preferences, discount impact, and subscription
behaviour to support strategic business decisions.

The project combines **Python (data cleaning & feature engineering),
PostgreSQL (SQL analysis), and Power BI (data visualization)** to
deliver actionable business insights.

------------------------------------------------------------------------

## Dataset Summary

-   **Total Records:** 3,900
-   **Total Columns:** 18
-   **Missing Data:** 37 missing values in the `Review Rating` column

### Key Features:

-   **Customer Demographics:** Age, Gender, Location, Subscription
    Status
-   **Purchase Details:** Item Purchased, Category, Purchase Amount,
    Size, Colour, Season
-   **Shopping Behaviour:** Discount Applied, Promo Code Used, Previous
    Purchases, Frequency of Purchases, Review Rating, Shipping Type

------------------------------------------------------------------------


## Data Cleaning & Preparation (Python)

-   Imported dataset using **Pandas**
-   Performed initial exploration using `df.info()` and `df.describe()`
-   Handled missing values using **median imputation by product
    category**
-   Standardized column names to **snake_case**
-   Created new features:
    -   `age_group`
    -   `purchase_frequency_days`
-   Removed redundant column (`promo_code_used`)
-   Loaded cleaned dataset into **PostgreSQL**

------------------------------------------------------------------------




## SQL Business Analysis (PostgreSQL)

The following key business questions were answered:

1.  Revenue by Gender
2.  High-Spending Discount Users
3.  Top 5 Products by Rating
4.  Shipping Type Comparison
5.  Subscribers vs Non-Subscribers
6.  Discount-Dependent Products
7.  Customer Segmentation (New, Returning, Loyal)
8.  Top 3 Products per Category
9.  Repeat Buyers & Subscription Analysis
10. Revenue by Age Group

------------------------------------------------------------------------

## Power BI Dashboard

An interactive Power BI dashboard was built to visualize:

-   Revenue trends
-   Customer segmentation
-   Product performance
-   Subscription behaviour
-   Discount impact

------------------------------------------------------------------------


## Business Recommendations

-   Promote exclusive benefits to increase subscriptions
-   Implement loyalty programs to convert returning customers into loyal
    customers
-   Optimize discount strategies to protect profit margins
-   Highlight top-rated and best-selling products in marketing
    campaigns
-   Focus targeted marketing on high-revenue age groups and
    express-shipping customers

------------------------------------------------------------------------




## Tools & Technologies

-   Python (Pandas)
-   PostgreSQL
-   Power BI
-   Data Cleaning & Feature Engineering
-   SQL Analytics

------------------------------------------------------------------------


## Project Outcome

This project demonstrates an end-to-end data analytics workflow: - Data
cleaning and preprocessing - Database integration - Business-driven SQL
analysis - Dashboard development - Strategic recommendations


