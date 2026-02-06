Task 13: BI Dashboard Storytelling — Executive KPI Report
📌 Project Overview

This project focuses on BI dashboard storytelling by building an executive-ready KPI report using Power BI Desktop / Tableau Public.
The objective is not just visualization, but communicating insights clearly to decision-makers through KPIs, trends, breakdowns, and narrative insights.

📂 Dataset

One of the following datasets was used:

Global Superstore Dataset (recommended)

Retail Sales Dataset

The dataset represents transactional sales data including products, categories, regions, dates, sales, and profit.

🛠 Tools & Technologies

Primary: Power BI Desktop (Free)

Alternative: Tableau Public (Free)

📁 Repository Structure
Task_13_BI_KPI_Storytelling/
│
├── dashboard.pbix
├── dashboard_export.pdf
├── insights_task13.txt
└── README.md

🔢 KPI Measures (Power BI – DAX)
Total Sales
Total Sales = SUM(Sales[Sales])

Total Profit
Total Profit = SUM(Sales[Profit])

Profit Margin
Profit Margin = DIVIDE([Total Profit], [Total Sales])

🔢 Tableau Calculated Fields (Alternative)
Total Sales = SUM([Sales])
Total Profit = SUM([Profit])
Profit Margin = SUM([Profit]) / SUM([Sales])

📊 Dashboard Components
1️⃣ KPI Cards (Top Section)

Total Sales

Total Profit

Profit Margin

Purpose: Provide quick executive snapshot.

2️⃣ Sales Trend Over Time (Line Chart)

X-axis: Order Date (Month/Year)

Y-axis: Total Sales

Purpose: Identify growth trends and seasonality.

3️⃣ Category Performance (Bar Chart)

Category vs Total Sales

Purpose: Identify revenue-driving categories.

4️⃣ Regional Performance (Map / Bar Chart)

Sales by Region

Purpose: Compare geographical performance.

5️⃣ Top 10 Products (Table)

Product Name

Total Sales

Total Profit

Purpose: Highlight high-impact products.

6️⃣ Interactive Slicers

Region

Category

Date

Purpose: Enable dynamic exploration of business performance.
