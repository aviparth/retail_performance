# Retail Business Performance Analysis

## 1. Executive Summary

This project analyzes retail sales performance using Power BI to provide a management-level view of revenue, orders, customer segments, product performance, and category performance. The dashboard is designed from a CEO/stakeholder perspective, focusing on key metrics required for business performance evaluation and data-driven decision-making.

Key KPIs include Total Revenue, Total Orders, Total Units Sold, Total Customers, and Average Order Value (AOV).

## 2. Business Problem

The business needs to understand how revenue is performing over time, which products generate the highest sales volume, which categories are driving or underperforming in revenue, which customer segments contribute the most revenue, and how efficiently orders are converted into revenue.

The objective was to transform raw transactional data into an interactive executive dashboard that highlights important business trends and areas requiring management attention.

## 3. Methodology

### Data Preparation
- Cleaned and prepared retail transaction data
- Standardized product and category information
- Checked data relationships and consistency
- Created a structured Star Schema data model
- Used invoice_items as the primary fact table
- Connected customer, product, and date dimensions

### Analysis
Created KPIs and measures for:
- Total Revenue
- Total Orders
- Total Units Sold
- Total Customers
- Average Order Value (AOV)
- Revenue by Customer Segment
- Revenue by Category
- Product-level sales performance
- Quarterly revenue trends

### Dashboard
Built an interactive Power BI dashboard containing:
- Revenue Trend by Quarter
- Top Products by Units Sold
- Category Revenue & Unit Performance
- Revenue by Customer Segment
- Lowest-Performing Categories by Revenue
- Top 5 Categories by Revenue
- Interactive Customer, Category, and Date filters

## 4. Skills

Tools & Technologies:
- Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning
- Data Visualization
- Business Analysis
- KPI Development
- Exploratory Data Analysis

Key Concepts:
- Star Schema
- Fact & Dimension Tables
- One-to-Many Relationships
- Time Intelligence
- Revenue Analysis
- Customer Segmentation
- Product Analysis
- Category Analysis

## 5. Results & Business Recommendations

### Key Findings
- Generated approximately ₹9.5M in revenue from 33.5K orders.
- Approximately 5.37M units were sold.
- Average Order Value was approximately ₹284.
- Wholesale customers contributed approximately 73% of revenue, making them the primary revenue segment.
- Kitchen & Dining was the highest-revenue category, followed by Home Decor.
- Several categories contributed significantly less revenue and may require further investigation.
- Revenue increased substantially between 2014 and 2015. However, this should be validated against order volume, AOV, data coverage, and potential business events before concluding that the increase represents organic growth.

### Business Recommendations
- Reduce excessive dependence on wholesale customers by developing the private/customer segment.
- Maintain inventory availability for high-volume products.
- Investigate low-performing categories to identify pricing, demand, or product assortment issues.
- Analyze the reasons behind the significant year-over-year revenue increase.
- Monitor AOV and order frequency to identify opportunities for increasing customer value.

## 6. Next Steps Company Should Take

1. Validate the 2014–2015 revenue increase against orders, units, AOV, and data completeness.
2. Analyze profit margins by product and category to identify which areas are actually most profitable.
3. Investigate customer retention and repeat purchase behavior.
4. Identify high-value wholesale customers and develop targeted retention strategies.
5. Analyze low-performing categories and determine whether to improve, reposition, or discontinue certain products.
6. Develop monthly/quarterly revenue forecasting to support inventory and business planning.
7. Track YoY revenue, AOV, units sold, and customer growth as ongoing management KPIs.
