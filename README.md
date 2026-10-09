Sales Analytics & Business Intelligence Portfolio (IBM Cognos Analytics)
A comprehensive analytics portfolio exploring multi-dimensional retail sales data (Zepto order-level dataset). This repository contains 6 structured practical lab implementations developed in IBM Cognos Analytics, culminating in an executive-ready Descriptive Analytics Report evaluating revenue patterns, discounting impacts, product profitability, and customer segmentation.
Repository Structure
├── Practicals/
│   ├── Practical 1.pdf    # Multi-dimensional Crosstab & Tabular Analysis
│   ├── Practical 2.pdf    # Hierarchical Grouped Sales Reporting & Aggregations
│   ├── Practical 3.pdf    # Time-Series Transactional Analysis & Filtered Views
│   ├── Practical 4.pdf    # Multi-Metric Matrix (Net Sales vs Quantity Matrix)
│   ├── Practical 5.pdf    # Focused Category Slicing & Deep-Dive Filtering
│   └── Practical 6.pdf    # Interactive BI Dashboard (KPIs, Trends & Segmentation)
└── Reports/
    └── PiyushKumarYadav_1250258304_DescriptiveAnalyticsReport.pdf # Executive Descriptive Report


Practical Lab Overview
Practical 1: Multi-Dimensional Tabular Breakdown
Objective: Establish baseline revenue breakdown by cross-evaluating regional performance against core retail categories.
Key Focus: Tabular modeling of Region \times Category vs Net Sales.
Key Findings: Identified core performance splits across North, South, East, West, and Central regions.
Practical 2: Hierarchical Grouped Sales Reporting
Objective: Implement grouped summaries with subtotals across nested hierarchies (Region \rightarrow Product Category \rightarrow Product).
Key Focus: Volume (Qty) vs Revenue (Net Sales) tracking with subtotal and grand total rollup across regional levels.
Practical 3: Time-Series Transactional Auditing
Objective: Track chronological order flow, discount variations, and granular transaction performance.
Key Focus: Date-level drilldown (Order Date), regional filtering (e.g., North), and line-item revenue tracing.
Practical 4: Multi-Metric Matrix Analysis
Objective: Construct a dual-metric crosstab matrix evaluating dimensional interactions.
Key Focus: Side-by-side comparison of Net Sales and Qty across all 5 major categories (Furniture, Apparel, Electronics, Office Supplies, Home & Kitchen) broken down by region, validating total sales of ₹31,635 across 600 units.
Practical 5: Sliced Dimensional Deep Dive
Objective: Apply targeted dimensional filtering and slice-and-dice mechanisms.
Key Focus: Filtered metric extraction isolating specific product-region intersections (e.g., Running Shoes in the South region).
Practical 6: Interactive Executive BI Dashboard
Objective: Design an interactive, multi-visualization dashboard interface in IBM Cognos Analytics.
Key Visualizations:
Summary KPI Card: Total Active Customer count (80 distinct customers).
Time-Series Area/Line Chart: Temporal Net Sales trends across daily order cycles.
Segment Distribution Bar Chart: Customer count breakdown by segment (Consumer, Corporate, Home Office / Small Business).
Executive Report Summary




File: PiyushKumarYadav_1250258304_DescriptiveAnalyticsReport.pdf Author: Piyush Kumar Yadav Dataset Scope: 200 orders across 80 unique customers spanning January to July 2024 (Total Net Sales: ₹31,635; Gross Sales: ₹33,300).
Key Analytical Insights
Category Profitability & Volume:
Highest Revenue: Furniture (₹9,120) and Home & Kitchen (₹8,550) drove the largest gross sales.
Highest Profit Margin: Office Supplies led margins at 47.4%, followed by Home & Kitchen (41.6%) and Apparel (41.4%).
Top Product Efficiency: Webcam HD delivered the single highest profit margin (52.2%).
Regional Performance:
Central Region dominated sales (₹10,545; 33.3% share), followed by West (₹8,436; 26.7%).
North represented the smallest market footprint (₹2,109; 6.7%).
Discounting & Price Sensitivity:
Exactly 50% of orders received a 10% discount, accounting for ₹1,665 in total discounts surrendered.
Discounted orders showed no significant volume elasticity over undiscounted orders (100 orders each), suggesting potential margin cannibalization on non-promotional items.
Customer Segments & Payment Methods:
The Consumer segment generated the largest overall revenue pool, while Corporate carried the lowest average segment margin (≈32.1%) due to product mix and discounting.
Digital payment methods (UPI and Credit Cards) drove the majority of transactions, with Cash on Delivery showing lower basket values.
Tools & Technologies
Business Intelligence: IBM Cognos Analytics (Dashboarding, Report Studio, Crosstabs)
Analytics Techniques: Exploratory Data Analysis (EDA), Descriptive Statistics, Cohort & Customer Segmentation, Revenue & Margin Decomposition
