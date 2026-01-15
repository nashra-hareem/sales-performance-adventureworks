# sales-performance-adventureworks
Sales performance and customer segmentation analysis using Power BI (AdventureWorks dataset).
# Adventure Works Analytics Suite

## Executive Overview

The **Adventure Works Analytics Suite** is a multi-page Power BI reporting solution designed to deliver a comprehensive, business-ready view of sales performance, product profitability, customer behavior, and geographic trends.

Built using a **star schema data model**, optimized **DAX measures**, and **interactive visual storytelling**, this project demonstrates end-to-end BI development — from data modeling to executive-level insights.

The solution is structured into four core dashboards, each answering a specific business question while maintaining consistent KPI logic, layout, and navigation.

---

## Dashboards Included

### 1. Executive Summary Dashboard

**Purpose**  
Provide leadership with a high-level snapshot of overall business performance.

**Key Features**
- Top-level KPIs: Revenue, Orders, Profit, Return Rate
- Month-over-Month performance indicators
- Multi-year revenue and order trends with seasonality
- Category-level performance (Accessories, Bikes, Clothing)
- Top 10 products by orders, revenue, and return rate
- Comparison of most ordered vs. most returned product types

**Business Value**  
Enables executives to quickly assess performance, identify anomalies, and determine where deeper analysis is required.

---

### 2. Product Detail Dashboard

**Purpose**  
Enable SKU-level analysis to support pricing, inventory, and product strategy decisions.

**Key Features**
- Dynamic product selector (SKU-level filtering)
- Monthly orders, revenue, and profit vs. target
- Price adjustment simulation using parameter-driven modeling
- Adjusted vs. total profit trend analysis
- Subcategory and category performance insights

**Business Value**  
Supports pricing optimization, product lifecycle management, and margin sensitivity analysis.

---

### 3. Customer Detail Dashboard

**Purpose**  
Analyze customer behavior, segmentation, and revenue contribution.

**Key Features**
- Unique customer count and growth tracking
- Revenue per customer metrics
- Orders segmented by income level, occupation, and gender
- Top customers by revenue and order frequency
- Monthly customer trends based on customer start date

**Business Value**  
Helps identify high-value segments, retention opportunities, and demographic trends influencing sales.

---

### 4. Geographic / Map Dashboard

**Purpose**  
Visualize sales performance across global territories.

**Key Features**
- Interactive map with regional filtering (North America, Europe, Pacific)
- Territory-level KPIs: revenue, orders, profit, returns
- Regional performance comparison

**Business Value**  
Supports regional planning, forecasting, and international sales strategy.

---

## Data Model & Technical Architecture

### Data Sources
- Sales fact table
- Returns data
- Customer, Product, Subcategory, Category, and Territory dimension tables
- Calendar table with rolling date logic

### Modeling Approach
- Star schema with clean, optimized relationships
- Dedicated Measures Table for organized DAX logic
- Parameter tables for:
  - Dynamic metric selection
  - Price adjustment simulations

### DAX Highlights
- Time intelligence (MoM, YoY, rolling periods)
- KPI vs. goal comparisons
- Return rate calculations
- Profit sensitivity modeling
- Dynamic titles and metric switching

---

## Design & UX Principles

- Consistent layout and color palette across pages
- Clear KPI hierarchy for executive readability
- Interactive slicers and drill-through paths
- Tooltip pages to surface detail without clutter
- Business-first storytelling over decorative visuals

---

## Outcome & Skills Demonstrated

This project transforms raw transactional data into a **cohesive, decision-ready analytics experience** and demonstrates:

- Strong data modeling fundamentals  
- Advanced DAX and time intelligence proficiency  
- Executive-focused dashboard design  
- Business-oriented insight generation  
- Scalable, multi-page BI solution development  

**Target Audience:**  
Executives, product managers, marketing analysts, and operations teams.

---

## Tools Used
- Power BI
- DAX
- Star Schema Data Modeling
- Parameter Tables & What-If Analysis

---

## Author

**Nashra Hareem Masood**  
Supply Chain & Analytics Graduate  
Focus: Business Intelligence, Data Analytics, Decision Support Systems

---

*This repository is intended as a portfolio project showcasing practical, business-ready Power BI development.*
