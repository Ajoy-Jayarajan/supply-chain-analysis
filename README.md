<p align="center">
  <img src="images/banner.png" alt="Supply Chain Analytics Banner">
</p>

## Project Overview

This project focuses on analyzing a large-scale e-commerce supply chain dataset containing over **180,000 customer orders**. The objective was to investigate operational performance, customer purchasing behavior, profitability drivers, shipping efficiency, and revenue trends through business-oriented analytics.

Rather than performing only exploratory data analysis (EDA), the project was structured around **20 real-world business questions** commonly faced by supply chain managers, logistics teams, operations analysts, and business decision-makers.

The analysis aims to uncover actionable insights that can improve:
- Supply chain efficiency
- Delivery performance
- Customer satisfaction
- Profitability
- Revenue growth
- Risk management

---

## Business Objectives

The project was designed to answer the following business questions:

### Profitability Analysis
1. Which product categories generate the most profit per order?
2. Which categories operate at a loss despite strong sales?
3. How do discount rates affect profitability?

### Customer Analytics
4. Which customer segments generate the highest order value and profit margins?
5. What share of revenue comes from the top 20% of customers (Pareto Analysis)?
6. Which high-value customers show declining purchasing activity?

### Revenue Analysis
7. What are the year-over-year revenue trends by market?
8. Which markets are growing and which are declining?

### Supply Chain & Logistics Analysis
9. Which markets have the highest late delivery rates?
10. Which shipping mode and region combinations create the highest delivery risk?
11. Which regions experience the longest shipment delays?
12. Are premium products receiving better delivery service?

### Risk Analysis
13. Which markets have the highest fraud and cancellation rates?
14. What revenue is at risk from cancellations and suspected fraud?

### Operational Performance Analysis
15. Which weekdays and months experience delivery spikes?
16. Which departments suffer from the lowest profit margins?
17. Are high-value customer locations receiving adequate service levels?

### Pricing & Discount Analysis
18. Do larger orders receive higher discounts?
19. Do higher discounts increase cancellation rates?

---

# Dataset Information

The dataset contains detailed order-level information from an e-commerce supply chain system.

### Dataset Size

| Metric | Value |
|----------|----------|
| Total Records | 180,519+ |
| Customers | 20,000+ |
| Markets | 5 |
| Regions | 20+ |
| Product Categories | 50+ |
| Shipping Modes | 4 |

---

## Key Features Used

### Customer Information
- Customer ID
- Customer Segment
- Customer City
- Customer State

### Order Information
- Order ID
- Order Date
- Order Status
- Order Quantity

### Product Information
- Category Name
- Department Name
- Product Price

### Financial Metrics
- Sales
- Order Item Total
- Benefit Per Order
- Profit Ratio
- Discount Rate

### Logistics Metrics
- Shipping Mode
- Shipping Dates
- Scheduled Shipping Days
- Actual Shipping Days
- Late Delivery Risk

### Geographic Information
- Market
- Order Region

---

# Tools & Technologies

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Environment
- Jupyter Notebook

### Version Control
- Git
- GitHub

---

# Methodology

The project followed a structured analytics workflow:

### 1. Data Understanding
- Dataset exploration
- Data type inspection
- Feature identification

### 2. Data Cleaning
- Date conversion
- Feature engineering
- Derived metrics creation

### 3. Exploratory Data Analysis
- Descriptive statistics
- Trend analysis
- Correlation analysis

### 4. Business Analytics
- Profitability analysis
- Customer segmentation
- Pareto analysis
- Revenue trend analysis
- Logistics performance evaluation

### 5. Visualization
- Bar Charts
- Scatter Plots
- Trend Analysis Charts
- Comparative Analysis Visualizations

---

# Key Insights

## Customer Analytics

### Pareto Analysis

- Top 20% of customers contributed approximately **49.9% of total revenue**
- Revenue distribution is moderately concentrated rather than following the traditional 80/20 rule
- Business revenue is relatively diversified across the customer base

---

## Profitability Insights

### Most Valuable Customer-Segment & Shipping Combination

| Customer Segment | Shipping Mode | Avg Profit per Order |
|------------------|--------------|---------------------|
| Consumer | First Class | 24.81 |

### Least Valuable Combination

| Customer Segment | Shipping Mode | Avg Profit per Order |
|------------------|--------------|---------------------|
| Consumer | Same Day | 20.08 |

---

## Delivery Performance

### Late Delivery Analysis

- Late delivery rates exceed 50% across multiple regions
- Standard Class shipping contributes the largest volume of late deliveries
- Significant opportunities exist for improving logistics efficiency

---

## Revenue Analysis

### Growing Markets

- LATAM demonstrated stable revenue growth
- Europe showed strong growth but requires validation due to data inconsistencies

### Declining Markets

- USCA
- Africa
- Pacific Asia

These markets experienced substantial revenue declines in recent periods.

---

## Risk Analysis

### Cancellation & Fraud

Markets with the highest cancellation and suspected fraud proportions:

- USCA
- LATAM
- Europe

Revenue-at-risk patterns closely matched cancellation proportions.

---

## Product & Pricing Insights

### Discount Analysis

- No meaningful relationship was found between order quantity and discount rate
- Bulk orders do not appear to receive disproportionately larger discounts

### Premium Products

- Premium products showed slightly lower late-delivery risk
- Difference was minimal and does not conclusively indicate priority handling

---

# Skills Demonstrated

### Data Analysis
- Exploratory Data Analysis (EDA)
- Business KPI Analysis
- Revenue Analysis
- Customer Segmentation

### Supply Chain Analytics
- Logistics Performance Analysis
- Shipping Delay Analysis
- Delivery Risk Evaluation
- Operational Efficiency Assessment

### Business Analytics
- Profitability Analysis
- Pareto Analysis
- Trend Analysis
- Root Cause Investigation

### Python & Visualization
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# Author

Ajoy Jayarajan
