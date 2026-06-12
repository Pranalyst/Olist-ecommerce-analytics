# Olist E-Commerce Analytics Project

## Project Overview

This project presents an end-to-end analysis of the Olist Brazilian E-Commerce dataset using SQL and Power BI. The objective was to analyze customer behavior, product performance, seller performance, and overall marketplace trends to generate actionable business insights.

The project follows a complete analytics workflow, including data exploration, SQL-based business analysis, creation of analytical views, dashboard development in Power BI, and business recommendations.

---

## Business Objectives

The analysis was designed to answer the following business questions:

* Which product categories generate the highest revenue?
* How is revenue distributed across customers, products, and sellers?
* What percentage of customers are repeat buyers?
* Which customer segments contribute the most revenue?
* How concentrated is marketplace revenue among top sellers?
* What opportunities exist to improve customer retention and business growth?

---

## Dataset Information

The project uses the Olist Brazilian E-Commerce dataset containing customer, order, payment, product, seller, review, and geographic information.

### Tables Used

| Table          | Description                      |
| -------------- | -------------------------------- |
| customers      | Customer information             |
| orders         | Order details and status         |
| order_items    | Products purchased in each order |
| order_payments | Payment transactions             |
| order_reviews  | Customer review data             |
| products       | Product information              |
| sellers        | Seller information               |
| geo            | Geographic information           |
| category_trans | Product category translations    |

---

## Tech Stack

* SQL (MySQL)
* Power BI
* Git & GitHub
* VS Code

---

## Project Workflow

```text
Raw Dataset
      ↓
Data Audit & Validation
      ↓
SQL Business Analysis
      ↓
Analytical Views Creation
      ↓
Power BI Data Modeling
      ↓
Dashboard Development
      ↓
Business Insights & Recommendations
```

---

## Dashboard Pages

### 1. Executive Overview

Provides a high-level view of marketplace performance through key business metrics:

* Total Revenue
* Total Orders
* Total Customers
* Total Sellers
* Average Review Score
* Repeat Customer Rate

---

### 2. Customer Analytics

Focuses on customer segmentation and purchasing behavior.

Key analyses:

* Customer Value Segmentation
* Repeat vs One-Time Buyers
* Revenue Contribution by Customer Segment
* Customer Spending Patterns

---

### 3. Product & Revenue Analytics

Evaluates product category performance and revenue drivers.

Key analyses:

* Revenue by Category
* Orders by Category
* Revenue Contribution Analysis
* Revenue vs Review Score Analysis

---

### 4. Seller Analytics

Analyzes seller performance and marketplace contribution.

Key analyses:

* Seller Revenue Segmentation
* Revenue Distribution by Seller Segment
* Seller Revenue vs Review Score
* Seller Performance Evaluation

---

## Key Business Findings

* High Value Customers represent only 4.57% of customers but contribute 25.53% of total revenue.
* The repeat customer rate is only 3.0%, indicating a significant opportunity for customer retention initiatives.
* Health & Beauty, Watches, and Bed/Bath/Table are the highest revenue-generating categories and collectively contribute 26.17% of total revenue.
* Top Revenue Sellers contribute 29.21% of marketplace revenue, demonstrating seller concentration.
* Revenue generation is highly concentrated among a relatively small group of customers, categories, and sellers.

---

## Strategic Recommendations

### Improve Customer Retention

Implement loyalty programs and personalized marketing campaigns to increase repeat purchases.

### Prioritize High-Value Customers

Develop retention strategies focused on customers with the highest revenue contribution.

### Expand High-Performing Categories

Increase investment in categories with strong revenue and customer satisfaction performance.

### Strengthen Seller Quality Monitoring

Track seller performance metrics and customer reviews to maintain marketplace quality standards.

---

## Repository Structure

```text
olist/

├── olist_analytics/
│   ├── data_audit_01.sql
│   ├── business_kpi_02.sql
│   ├── revenue_analysis_03.sql
│   ├── customer_analysis_04.sql
│   ├── order_analysis_05.sql
│   ├── logistics_delivery_analysis_06.sql
│   ├── product_category_analysis_07.sql
│   ├── seller_analysis_08.sql
│   ├── rfm_09.sql
│   ├── business_insights_10.sql
│   └── views.sql

├── olist.pbix

├── reports/
│   ├── business_findings.md
│   ├── executive_summary.md
│   └── data_dictionary.md

├── images/
│   ├── Customer_segment_distribution.png
│   ├── Executive_overview.png
│   ├── Product_and_Revenue_analytics.png
│   └── Seller_analytics.png

└── README.md
```

---

## Conclusion

This project demonstrates the use of SQL and Power BI to transform raw transactional data into actionable business insights. The analysis highlights key opportunities in customer retention, category growth, and seller performance management while providing an end-to-end example of a real-world data analytics workflow.
