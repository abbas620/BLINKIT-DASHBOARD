🛒 Blinkit Grocery Sales Performance Dashboard
A Power BI Business Intelligence Project 

Overview
This project presents an interactive Power BI dashboard built on Blinkit's grocery sales dataset. Blinkit, formerly known as Grofers, is one of India's leading quick-commerce platforms offering last-minute grocery delivery. The goal of this project was to analyze sales performance, product trends, outlet efficiency, and customer satisfaction across multiple outlet types, sizes, and city tiers — transforming raw transactional data into actionable business intelligence.

Business Problem
Blinkit operates a large and diverse network of grocery outlets spread across Tier 1, Tier 2, and Tier 3 cities in India. Despite generating significant sales volumes, the business lacked a centralized and visual way to monitor performance across its outlet network. Decision-makers found it difficult to identify which outlet types, product categories, and geographic locations were contributing most to revenue. There was also no clear visibility into customer satisfaction trends or how outlet establishment year correlated with sales performance. This dashboard was built to solve that problem by consolidating all key metrics into a single, interactive, and easy-to-navigate interface.

Project Objective
The primary objective of this project was to design and develop a comprehensive Power BI dashboard that provides end-to-end visibility into Blinkit's grocery sales data. The dashboard enables business stakeholders to monitor KPIs at a glance, drill down into product and outlet-level performance, identify high-performing and underperforming segments, and support data-driven decisions around retail strategy, inventory planning, and outlet expansion.

Dataset Description
The dataset used in this project is the Blinkit Grocery Data, which contains transactional-level records across multiple outlets and product categories. The key fields in the dataset include Item Identifier, Item Type, Item Fat Content, Item Visibility, Outlet Identifier, Outlet Establishment Year, Outlet Location Type (Tier 1 / Tier 2 / Tier 3), Outlet Size (Small / Medium / High), Outlet Type (Grocery Store / Supermarket Type 1, 2, 3), Item Rating, and Sales figures.
The dataset covers sales data from 2012 to 2022 and includes over 9,000 unique items across 16+ product categories.

Dashboard Features
The dashboard is structured across two pages — the main analytics view and a detailed data table view — and includes the following components.
KPI Summary Cards display the four most critical business metrics at the top of the dashboard: Total Sales of $1.20M, Average Sales per item of $140.99, Total Items count of 9K, and Average Customer Rating of 3.92. These cards give stakeholders an instant snapshot of overall business health.
Fat Content Analysis uses a donut chart to break down total sales between Low Fat and Regular products. An additional grouped bar chart shows this split further across Tier 1, Tier 2, and Tier 3 outlet locations, helping the business understand health-conscious buying behavior by geography.
Item Type Performance is visualized through a horizontal bar chart that compares Total Sales and Average Sales across all 16+ product categories including Fruits & Vegetables, Snack Foods, Household Items, Frozen Foods, Dairy, Canned Goods, Baking Goods, Health & Hygiene, Meat, Soft Drinks, Breads, Hard Drinks, and others.
Outlet Size Distribution is represented through a donut chart showing the revenue contribution of Small, Medium, and High-sized outlets. High-size outlets contribute 42.27% of total revenue, Medium outlets contribute 37.01%, and Small outlets contribute 20.72%.
Outlet Location Performance uses a horizontal bar chart to compare total sales across Tier 1, Tier 2, and Tier 3 cities. Tier 3 cities lead with $472.13K in sales, followed by Tier 2 at $393.15K and Tier 1 at $336.40K.
Outlet Establishment Trend is a line and area chart tracking yearly sales performance from 2012 to 2022. It reveals how sales grew from $78K in 2012, peaked at $205K in 2018, and then stabilized around $131K in subsequent years.
Outlet Type Comparison Table provides a detailed breakdown across four outlet types — Grocery Store, Supermarket Type 1, Supermarket Type 2, and Supermarket Type 3 — showing Total Sales, Total Items, Average Sales, Average Rating, and Average Item size for each.
Dynamic Filter Panel allows users to slice and filter the entire dashboard by Outlet Location (Tier 1 / Tier 2 / Tier 3), Outlet Size (Small / Medium / High), and Item Type — enabling targeted drill-down analysis for any business question.

Key Insights
Supermarket Type 1 is the highest-performing outlet type with $787.55K in total sales and 5,577 items, making it the dominant channel in Blinkit's retail network. Tier 3 cities generate the most revenue at $472.13K, which is a counterintuitive finding that highlights strong grocery demand in smaller cities and presents a significant growth opportunity. Sales peaked in 2018 at $205K but declined post-2018, suggesting that the business may need to revisit its expansion and retention strategies for that period. Fruits & Vegetables and Snack Foods are consistently the top-selling product categories, indicating high daily demand for fresh and convenience items. Average customer ratings remain stable at approximately 3.92 across all outlet types, reflecting consistent service quality across the network. Regular fat content products outsell Low Fat products significantly, though the Low Fat segment shows growing presence, particularly in Tier 1 outlets.

Tools and Technologies Used
This project was built entirely using Microsoft Power BI for data modeling, DAX calculations, and dashboard design. The raw data was sourced from an Excel  file and cleaned and structured within Power BI's Power Query Editor. DAX measures were written to calculate KPIs such as Total Sales, Average Sales, and Average Rating dynamically across all filter contexts.

Skills Demonstrated
Through this project, the following skills were applied and demonstrated: data cleaning and transformation using Power Query, data modeling and relationship management in Power BI, DAX measure creation for dynamic KPI calculations, interactive dashboard design with slicers and cross-filtering, business insight generation from retail and e-commerce data, and data storytelling through visual hierarchy and layout design.

How to Use This Dashboard
To explore the dashboard, open the .pbix file in Microsoft Power BI Desktop. Use the Filter Panel on the left side to slice the data by Outlet Location, Outlet Size, or Item Type. Click on any chart element to cross-filter the entire dashboard. Switch between the main dashboard tab and the Table tab to view raw transactional data. Hover over any visual to see detailed tooltips with exact values.
