# 📊 Digital-Marketing-Sales-Analysis - Power BI Dashboard

An interactive multi-page Power BI dashboard that analyzes digital marketing campaign performance across platforms, ad formats, and time periods — helping businesses maximize revenue and optimize ad spend.

## 📌 Short Description & Purpose

This project analyzes digital marketing sales data from multiple campaigns running across platforms like Google Ads, Facebook Ads, and YouTube Ads to uncover what drives revenue, conversions, and profitability. It was built to help a multinational e-commerce company monitor campaign effectiveness, track budget utilization, and identify which platform and ad format combinations deliver the highest ROI. The dashboard empowers marketing and finance teams to make data-driven decisions — from reallocating ad budgets to doubling down on high-performing campaigns.

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Multi-page dashboard design, DAX measures, data modeling |
| **Power Query (M Language)** | Data transformation and cleaning |
| **DAX (Data Analysis Expressions)** | KPI calculations — ROI %, Profit Margin, Budget Utilization, Avg CPC/CPM |
| **Excel / CSV** | Source data format |
| **.pbit (Power BI Template)** | Reusable, shareable dashboard template |

## 📂 Data Source

- **Type:** Digital marketing transactional dataset from a multinational e-commerce company
- **Platforms Covered:** Google Ads, Facebook Ads, YouTube Ads (Platform A, B, C, D)
- **Campaigns:** Campaign 1, Campaign 2, Campaign 3
- **Ad Formats:** Display Ads, Overlay Ads, Skippable Ads, Non-Skippable Ads, Bumper Ads
- **Years:** 2017 – 2020
- **Key Metrics Tracked:**

| Metric Group | Fields |
|---|---|
| Traffic | Impressions, Clicks, Avg Pages Visited, Avg Time on Site |
| Conversions | Total Conversions, Quantity Sold |
| Financials | Unit Cost Price, Unit Sale Price, Final Cost Price, Final Sale Price |
| Performance | ROI %, Profit Margin %, Budget Utilization %, CPC, CPM |

## ✨ Features & Highlights

The dashboard is organized across **5 interactive pages:**

**Page 1 — Digital Marketing Sales Analysis (Overview)**
- KPI Cards: Total Sales (113.33M), Total Cost (35.84M), Total Profit (77.49M), ROI % (21,623.82%), Budget Utilization (99.55%)
- Total Sales & Profit by Platform across all 3 campaigns (stacked bar charts)
- Sales Target gauge showing actual vs. target performance
- Monthly Sales Trends line chart across Jan–Dec

**Page 2 — Campaign & Platform Analysis**
- Ad Campaign total sales breakdown by platform
- Profit Margin % by Platform — consistently ~68% across all platforms
- Sum of Conversions by Platform pie chart — Platform B leads at 38.03%
- Detailed matrix: Sales, Cost, Profit & ROI % per Campaign–Platform combination

**Page 3 — Cost Analysis**
- KPI Cards: Avg CPC (2.04) and Avg CPM (5.13)
- Avg CPC by Platform — near-uniform cost per click across all platforms
- Avg CPM by Platform — Platform D has the highest CPM (6+)
- Multi-metric log-scale chart: Impressions, Conversions, Clicks & Quantity Sold

**Page 4 — Target vs Actual Performance**
- % Achievement KPI: 144.19% — exceeding target
- Budget Remaining: 163.10K
- Gauge charts: Total Sales vs Target (113.33M / 226.66M) and Total Cost vs Ad Budget (35.84M / 71.67M)
- Total Sales & Total Target by Month (dual-line trend)

**Page 5 — Trends & Insights**
- Year (2017–2020) and Month (Jan–Dec) slicers for time-based drill-down
- Total Ad Format Sales by Month (area chart)
- Total Quantity Sold by Month — peaks in Nov–Dec
- Campaign × Platform decomposition tree map
- Monthly Sales by Platform waterfall chart (Increase / Decrease / Total)

## ❓ Key Business Questions Answered

1. What are the total sales, cost, profit, and ROI across all campaigns and platforms?
2. Which platform generates the highest total sales and total profit?
3. Which Campaign–Platform combination delivers the best ROI percentage?
4. How does actual budget utilization compare against the predefined ad spend limit?
5. Are total sales on track to meet the overall sales target?
6. Which platform has the highest average CPM and what does that mean for cost efficiency?

## 📸 Dashboard Screenshots
![Digital Marketing Sales Analysis Overview](https://github.com/vaibhavichavan/Digital-Marketing-Sales-Analysis/blob/main/Dashboard.pdf)
