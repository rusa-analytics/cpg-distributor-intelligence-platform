# CPG Distributor Intelligence Platform

<img width="1254" height="1254" alt="logo" src="https://github.com/user-attachments/assets/eba15845-1d60-435d-877d-0230de2d35dd" />

## AI-Powered Insights. Business-Driven Outcomes.

An enterprise-grade CPG Distributor Intelligence Platform developed by RUSA Analytics to help global consumer goods organizations improve distributor performance, optimize market coverage, enhance product visibility, and accelerate data-driven decision-making.

---

# Executive Summary

Apex Consumer Group is a fictional multinational Consumer Packaged Goods (CPG) organization operating across global markets.

### Business Scale

- $1.2 Billion Annual Revenue
- 18 Countries
- 300 Distributors
- 35,000 Retail Outlets
- 150 Products
- 250,000+ Sales Transactions

As the business expanded globally, leadership faced challenges in understanding distributor effectiveness, market penetration, product contribution, and regional growth opportunities.

To address these challenges, RUSA Analytics designed and developed a CPG Distributor Intelligence Platform that provides executives, sales leaders, and regional managers with a unified view of performance across the entire distribution network.

---

# Business Challenge

Global CPG organizations often struggle with:

- Limited visibility into distributor performance
- Fragmented reporting across countries and regions
- Inconsistent market coverage
- Lack of SKU-level performance insights
- Difficulty tracking target achievement
- Delayed executive reporting
- Siloed data sources across ERP, CRM, and sales systems

Leadership required a centralized intelligence platform capable of delivering actionable insights across the distribution ecosystem.

---

# Solution Overview

The CPG Distributor Intelligence Platform consolidates sales, distributor, outlet, and product data into a unified intelligence layer.

The platform enables:

- Executive Performance Monitoring
- Distributor Performance Analysis
- Product Intelligence
- Regional Intelligence
- Market Coverage Analytics
- Strategic Decision Support
- AI-Powered Insights

### Scalable Enterprise Architecture

The solution is designed for enterprise-scale deployment and can integrate with modern analytics ecosystems including:

- Databricks
- Snowflake
- Microsoft Azure
- Amazon Web Services (AWS)
- Power BI
- Tableau
- Generative AI Platforms
- Agentic AI Frameworks

---

# Enterprise Architecture

```text
ERP Systems
CRM Systems
Distributor Data
Retail Sales Data
Marketing Data

        ↓

Databricks / Snowflake

        ↓

Data Engineering Layer
SQL + Python

        ↓

Power BI / Tableau

        ↓

Executive Intelligence Platform

        ↓

Business Leaders & Decision Makers
```

---

# Platform Modules

## 1. Executive Intelligence

Provides a high-level view of business performance.

### Key Metrics

- Global Revenue
- Gross Profit
- Gross Margin %
- Units Sold
- Active Distributors
- Active Outlets
- Market Penetration %
- Revenue Growth %

### Key Visualizations

- Revenue Trend Analysis
- Revenue by Region
- Revenue by Category
- Revenue by Channel
- Executive Insights Panel

---

## 2. Distributor Intelligence

Provides visibility into distributor effectiveness and target achievement.

### Key Metrics

- Distributor Revenue
- Target Achievement %
- Active Distributors
- High Performing Distributors
- Underperforming Distributors

### Key Visualizations

- Top 10 Distributors
- Bottom 10 Distributors
- Target vs Actual Performance
- Distributor Segmentation
- Performance Heatmap

---

## 3. Product Intelligence

Enables product portfolio optimization.

### Key Metrics

- Product Revenue
- Units Sold
- Active SKUs
- Average Selling Price
- Product Growth %

### Key Visualizations

- Product Pareto Analysis
- Category Mix
- Top Products
- Bottom Products
- Product Performance Summary

---

## 4. Regional Intelligence

Provides geographic performance visibility.

### Key Metrics

- Revenue by Region
- Revenue by Country
- Growth by Region
- Market Contribution

### Key Visualizations

- Country Performance Analysis
- Regional Revenue Trends
- Global Revenue Distribution
- Geographic Heatmaps

---

## 5. Market Coverage Intelligence

Measures distribution reach and market penetration.

### Key Metrics

- Active Outlets
- Covered Markets
- Market Penetration %
- New Outlet Additions
- Coverage Gaps

### Key Visualizations

- Coverage Analysis
- Market Reach Metrics
- Outlet Distribution
- Growth Opportunities

---

# Dataset Overview

The platform uses enterprise-scale simulated data.

## Distributor Master

Contains:

- Distributor ID
- Distributor Name
- Region
- Country
- Distributor Type
- Status

Records:
300

---

## Outlet Master

Contains:

- Outlet ID
- Outlet Name
- Outlet Type
- Country
- City
- Distributor

Records:
35,000

---

## Product Master

Contains:

- SKU ID
- Product Name
- Brand
- Category
- Unit Price

Records:
150

---

## Sales Transactions

Contains:

- Transaction Date
- Distributor
- Outlet
- Product
- Units Sold
- Revenue
- Cost
- Profit

Records:
250,000+

---

## Target Data

Contains:

- Monthly Targets
- Revenue Targets
- Volume Targets
- Distributor Targets

Records:
7,200+

---

# Technology Stack

## Business Intelligence & Visualization

- Microsoft Power BI
- Tableau
- Executive Reporting
- Decision Intelligence

## Data Engineering & Analytics

- Databricks
- Snowflake
- SQL
- Python
- Data Modeling

## Cloud Platforms

- Microsoft Azure
- Amazon Web Services (AWS)
- Cloud Data Warehousing
- Enterprise Data Platforms

## Artificial Intelligence

- Generative AI
- Agentic AI
- Predictive Analytics
- AI-Powered Insights
- Intelligent Automation

## Frontend Demonstration

- HTML5
- CSS3
- JavaScript
- Chart.js
- Responsive Design

## Deployment

- GitHub Pages
- Azure
- AWS
- Enterprise Cloud Infrastructure

---

# Business Impact

The platform empowers leadership teams to:

### Improve Distributor Performance

Identify high-performing and underperforming distributors.

### Increase Market Coverage

Detect underserved regions and growth opportunities.

### Optimize Product Portfolio

Understand product contribution and category performance.

### Accelerate Decision Making

Deliver executive-ready insights through a centralized intelligence platform.

### Enhance Revenue Visibility

Track revenue, profitability, and growth across global markets.

### Support AI-Driven Decisions

Leverage analytics and AI to identify trends, risks, and opportunities faster.

---

# Screenshots

## Executive Intelligence

<img width="3840" height="2160" alt="RUSA_CPG_p1" src="https://github.com/user-attachments/assets/3a7dd9c4-d60e-4d81-8733-f8ba67e7ff1e" />

---

## Distributor Intelligence

<img width="3840" height="2160" alt="RUSA_CPG_p2" src="https://github.com/user-attachments/assets/89ebff69-8500-4468-904e-3b6516ca29b8" />


---

## Product Intelligence

 <img width="3840" height="2160" alt="RUSA_CPG_p3" src="https://github.com/user-attachments/assets/f89ded4d-24fb-477d-aefb-efcd1482bf01" />


---

## Regional Intelligence

<img width="3840" height="2160" alt="RUSA_CPG_p5" src="https://github.com/user-attachments/assets/eeed19ce-285e-4048-b9f7-5d6be19f05f2" />

---

## Market Coverage Intelligence

<img width="3840" height="2160" alt="RUSA_CPG_p4" src="https://github.com/user-attachments/assets/bc9b6a63-fa25-4b6b-8b19-2d35ee9e47bb" />

---

# Repository Structure

```text
cpg-distributor-intelligence-platform/


├── datasets/
│   ├── distributor_master.csv
│   ├── outlet_master.csv
│   ├── product_master.csv
│   ├── sales_transactions.csv
│   ├── target_data.csv
│   └── coverage_summary.csv

├── screenshots/
│   ├── executive-intelligence.png
│   ├── distributor-intelligence.png
│   ├── product-intelligence.png
│   ├── regional-intelligence.png
│   └── market-coverage.png

└── README.md
```

---

# Deployment Guide

## GitHub Pages

1. Create a new GitHub repository
2. Upload all project files
3. Navigate to Settings → Pages
4. Select:

Deploy from Branch

5. Choose:

Main Branch
Root Folder

6. Save

GitHub will generate a public URL for the platform.

---

# About RUSA Analytics

RUSA Analytics is an Enterprise AI & Analytics company helping organizations transform raw data into actionable business intelligence.

### Core Services

- Business Intelligence
- Data Analytics
- Decision Intelligence
- Generative AI
- Agentic AI
- Data Engineering
- Data Automation
- Executive Reporting
- Cloud Analytics
- Enterprise Intelligence Platforms

### Website

https://www.rusaanalytics.com

### LinkedIn

https://www.linkedin.com/company/rusa-analytics

### YouTube

https://www.youtube.com/@rusaanalytics

📖 Case Study: https://www.rusaanalytics.com/case-studies/cpg-distributor-intelligence-platform

💻 GitHub Repository: https://github.com/rusa-analytics/cpg-distributor-intelligence-platform

---

# Disclaimer

This project is a portfolio case study developed by RUSA Analytics using simulated enterprise-scale data for demonstration, educational, and showcase purposes.

No real company, distributor, customer, or confidential business information has been used.

---

## RUSA Analytics

### AI-Powered Insights. Business-Driven Outcomes.
