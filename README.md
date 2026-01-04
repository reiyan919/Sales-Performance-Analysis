Sales Performance Analysis & Forecasting Dashboard
📌 Project Overview

This project analyzes transactional retail data to uncover customer behavior, geographical performance, and sales seasonality, and to provide a predictive sales forecast.
The goal is to transform raw sales data into actionable business insights using data analysis, customer segmentation, and visualization.

The project follows a full data analytics workflow:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Customer segmentation (RFM)

Time-series sales forecasting

Interactive dashboard creation

📂 Dataset Description

Source: UCI Machine Learning Repository – Online Retail Dataset

Data type: Transactional retail data

Period: One full year

Main features:

InvoiceDate

CustomerID

Country

Quantity

UnitPrice

Sales (Quantity × UnitPrice)

📎 Dataset link:
https://archive.ics.uci.edu/ml/datasets/online+retail

This dataset represents real-world online retail transactions from a UK-based retailer, making it suitable for customer analytics and sales performance studies.

🎯 Project Objectives

Identify top-performing countries and customers

Analyze monthly sales trends and seasonality

Segment customers using RFM (Recency, Frequency, Monetary) analysis

Forecast future sales revenue

Communicate insights through an interactive Tableau dashboard

🧠 Methodology
1️⃣ Data Preparation

Removed canceled transactions and invalid records

Created new features (Sales, InvoiceMonth)

Handled missing CustomerID values (excluded from customer ranking analysis)

Best practices followed according to IBM Data Quality standards:
https://www.ibm.com/topics/data-quality

2️⃣ Exploratory Data Analysis (EDA)

Key analyses included:

Total sales, quantity, and customer counts

Sales and quantity by country

Monthly sales trend analysis

Findings confirm strong market concentration in the United Kingdom, with secondary European markets contributing smaller shares.

Reference (Retail market concentration – OECD):
https://www.oecd.org/industry/retail/

3️⃣ Customer Segmentation (RFM Analysis)

Customers were segmented using:

Recency: Time since last purchase

Frequency: Number of purchases

Monetary: Total spending

This approach helps identify:

High-value customers

Loyal customers

At-risk customers

RFM is a widely used industry standard in customer analytics:
https://www.sciencedirect.com/topics/business-economics/rfm-analysis

4️⃣ Sales Forecasting

Monthly sales were aggregated and analyzed using simple, interpretable models:

Moving Average

Linear Regression (trend-based forecasting)

The objective was business interpretability, not algorithmic complexity.

Sales forecasting fundamentals reference:
https://otexts.com/fpp2/

5️⃣ Data Visualization (Dashboard)

An interactive Tableau dashboard was created to present:

KPIs (Total Sales, Customers, Quantity)

Sales by country

Monthly sales trends

Top customers

Geographical sales distribution

The dashboard enables data-driven decision-making for non-technical stakeholders.

Best practices in data visualization:
https://hbr.org/2017/01/why-analytics-is-the-new-competitive-advantage

📈 Key Insights

The United Kingdom is the dominant market, reflecting dataset origin and domestic customer preference.

A small group of customers generates a large portion of revenue, confirming the Pareto principle in retail.

Sales peak in November, likely driven by seasonal promotions such as Black Friday and pre-holiday discounts.

These patterns highlight opportunities for targeted marketing, customer retention, and seasonal planning.

Seasonality reference (National Retail Federation):
https://nrf.com/research/holiday-and-seasonal-trends

🛠 Tools & Technologies

Python: Pandas, NumPy, Scikit-learn

Visualization: Tableau

Analysis techniques: RFM, EDA, time-series aggregation


📊 Tableau Dashboard:
https://public.tableau.com/app/profile/rayan.ra4401/viz/CustomerSegmentationSalesPerformanceDashboard/Dashboard1
