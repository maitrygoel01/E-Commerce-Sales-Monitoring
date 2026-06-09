# 🛒 E-Commerce Sales & Customer Analytics Dashboard

## 📌 Project Overview

The **E-Commerce Sales & Customer Analytics Dashboard** is an interactive Power BI solution designed to analyze sales performance, profitability, product performance, regional trends, and shipping efficiency across an e-commerce business.

The dashboard provides stakeholders with a comprehensive view of business performance through key sales KPIs, category-level analysis, product insights, geographic trends, and customer segment reporting.

By combining revenue, profit, quantity sold, and profit margin metrics into a single reporting platform, the dashboard enables data-driven decision-making for sales growth and operational optimization.

---

## 🎯 Business Problem

E-commerce businesses generate large volumes of transactional data across multiple products, customer segments, regions, and shipping methods.

Without centralized reporting, it becomes difficult to answer critical business questions such as:

- How are sales performing year-to-date?
- Which product categories drive the most revenue?
- Which products are top performers?
- Which products require strategic intervention?
- Which regions contribute the highest sales?
- How do shipping methods impact business performance?
- How are different customer segments performing?

This dashboard addresses these challenges through interactive visualizations and KPI-driven insights.

---

# 📊 Executive KPIs

| KPI | Value |
|------|--------|
| YTD Sales | $11.53M |
| YTD Profit | $1.34M |
| YTD Quantity Sold | 107.2K |
| Profit Margin | 11.58% |

---

## Performance Comparison

| KPI | Change vs Previous Year |
|------|------------------------|
| Sales | -0.83% |
| Profit | +4.50% |
| Quantity Sold | -7.29% |
| Profit Margin | +5.37% |

### Key Insight

Although overall sales volume declined slightly, profitability improved significantly due to higher margins and improved product mix.

---

# 🔷 Dashboard Analysis

## Business Questions Answered

- What is the overall sales performance?
- How profitable is the business?
- Which categories contribute the most revenue?
- Which products generate the highest sales?
- Which products underperform?
- Which regions drive the most sales?
- Which shipping methods contribute the highest revenue?
- How do customer segments differ in performance?

---

# 📈 Sales Performance Analysis

The dashboard tracks Year-to-Date performance across key metrics.

### Metrics Monitored

- Sales Revenue
- Profit
- Quantity Sold
- Profit Margin

### Key Insights

- Generated **$11.53M** in total sales.
- Achieved **$1.34M** profit.
- Sold over **107K units**.
- Maintained an overall **11.58% profit margin**.

---

# 🏷️ Category Performance Analysis

Sales performance is segmented across major product categories.

## Categories Analyzed

### Office Supplies

| Metric | Value |
|----------|----------|
| YTD Sales | $6.92M |
| Previous Year Sales | $7.00M |
| YoY Growth | -1.22% |

---

### Furniture

| Metric | Value |
|----------|----------|
| YTD Sales | $2.52M |
| Previous Year Sales | $2.50M |
| YoY Growth | +0.73% |

---

### Technology

| Metric | Value |
|----------|----------|
| YTD Sales | $2.10M |
| Previous Year Sales | $2.13M |
| YoY Growth | -1.37% |

---

## Business Insights

- Office Supplies contribute the largest share of revenue.
- Furniture is the only category showing positive year-over-year growth.
- Technology sales require further performance investigation.

---

# 🏆 Product Performance Analysis

The dashboard identifies both high-performing and underperforming products.

---

## Top 5 Products by Sales

Examples include:

- Staple Envelope
- Staples
- Easy-Staple Paper
- KI Adjustable Desk Accessories
- Other High Revenue Products

### Business Value

- Identify best-selling products.
- Optimize inventory planning.
- Support promotional strategies.

---

## Bottom 5 Products by Sales

Examples include:

- Eldon Jumbo Products
- Lexmark Accessories
- Cisco Products
- Xerox Products
- Rediform Products

### Business Value

- Product rationalization.
- Inventory optimization.
- Pricing strategy improvements.

---

# 🌎 Regional Sales Analysis

The dashboard provides a geographic breakdown of sales performance across the United States.

---

## Regional Segments

- West
- East
- Central
- South

### Analysis Includes

- Sales contribution by region.
- Geographic sales concentration.
- State-level sales distribution.

### Business Value

- Regional performance tracking.
- Territory optimization.
- Market expansion planning.

---

# 🗺️ State-Level Sales Analysis

An interactive map visualizes sales distribution across states.

### Insights Generated

- High-performing sales territories.
- Revenue concentration by location.
- Geographic demand patterns.

### Business Applications

- Resource allocation.
- Regional sales planning.
- Demand forecasting.

---

# 🚚 Shipping Performance Analysis

The dashboard evaluates revenue contribution across shipping methods.

## Shipping Types

- Standard Class
- Second Class
- First Class
- Same Day

### Key Insights

- Standard Class contributes the highest share of revenue.
- Premium shipping methods generate smaller sales volumes but may impact customer satisfaction.

### Business Value

- Logistics optimization.
- Shipping cost analysis.
- Fulfillment strategy planning.

---

# 👥 Customer Segment Analysis

The dashboard allows analysis across major customer groups.

## Available Segments

- Consumer
- Corporate
- Home Office

### Business Questions Answered

- Which customer segment drives the highest revenue?
- Which segment is most profitable?
- How do purchasing patterns vary by segment?

### Business Value

- Customer targeting.
- Segment-specific marketing.
- Revenue optimization.

---

# 📊 Key Business Insights

## Revenue Insights

- Total sales exceeded **$11.5M**.
- Profitability improved despite a slight sales decline.

---

## Product Insights

- A small group of products contributes a large share of revenue.
- Several low-performing products present optimization opportunities.

---

## Category Insights

- Office Supplies dominate total sales.
- Furniture shows positive growth momentum.

---

## Geographic Insights

- Sales are concentrated across specific regions and states.
- Geographic expansion opportunities exist in lower-performing markets.

---

## Operational Insights

- Standard shipping drives most transactions.
- Profit margins improved by more than **5% year-over-year**.

---

# 🛠️ Technical Implementation

## Data Modeling

The solution follows a Star Schema architecture.

### Fact Tables

- Fact Sales
- Fact Orders
- Fact Profit

### Dimension Tables

- Dim Product
- Dim Customer
- Dim Segment
- Dim Geography
- Dim Shipping
- Dim Date

---

## Power Query Transformations

Data preparation included:

- Data Cleaning
- Missing Value Handling
- Data Type Standardization
- Date Transformations
- Relationship Creation
- KPI Calculations

---

## DAX Measures

```DAX
YTD Sales

YTD Profit

YTD Quantity

Profit Margin %

Previous Year Sales

YoY Growth %

Top Product Sales

Regional Sales

Category Sales

Shipping Revenue

Sales by Segment
```

---


# 🧰 Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Transformation |
| DAX | Business Calculations |
| Excel / CSV | Data Source |
| Data Modeling | Star Schema Design |

---

# 📷 Dashboard Screenshot

## E-Commerce Sales Dashboard

<img width="1120" height="630" alt="image" src="https://github.com/user-attachments/assets/b1c49732-a799-4c6f-9422-a85b49d267fa" />

# 📂 Project Structure

```text
E-Commerce-Sales-Customer-Analytics-Dashboard/
│
├── Dataset/
│   └── Ecommerce_Sales_Data.xlsx
│
├── Dashboard/
│   └── Ecommerce_Sales_Analytics.pbix
│
├── Images/
│   └── ecommerce-sales-dashboard.png
│
└── README.md
```

---

# 📌 Conclusion

The **E-Commerce Sales & Customer Analytics Dashboard** provides a comprehensive business intelligence solution for monitoring revenue, profitability, product performance, customer segments, regional sales trends, and shipping effectiveness.

By transforming raw sales data into actionable insights, the dashboard empowers business stakeholders to optimize operations, improve profitability, and make informed strategic decisions.

### ⭐ Project Summary

> An interactive Power BI dashboard that analyzes e-commerce sales performance, profitability, customer segments, product trends, regional sales distribution, and shipping efficiency to support data-driven business decisions.
