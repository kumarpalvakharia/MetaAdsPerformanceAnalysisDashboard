# Meta Ads Performance Analysis Dashboard


This project analyzes Meta (Facebook & Instagram) advertising campaign data to track performance, understand audience engagement, and identify key insights for optimizing marketing strategies. The analysis culminates in an interactive Power BI dashboard designed to provide clear visibility into crucial KPIs.

## 📊 Power BI Dashboard Preview
Here is a preview of the final interactive dashboard, showcasing key performance indicators (KPIs), trends, and demographic breakdowns.

<img width="1316" height="802" alt="image" src="https://github.com/user-attachments/assets/4684a5c0-fecc-4a61-859d-6ad88b15c2f9" />

<img width="1317" height="802" alt="image" src="https://github.com/user-attachments/assets/53ab189b-faaf-484f-b096-fcdbf6656eb7" />



## 🎯 Business Objective
The primary goal of this project is to build a comprehensive BI dashboard to answer key business questions for the marketing team:

Which ad campaigns are providing the best Return on Investment (ROI)?

What is the performance difference between platforms (Facebook vs. Instagram)?

Which ad types and audience demographics are driving the most engagement and conversions?

How should the marketing budget be allocated to maximize performance?

## 📈 Key KPIs Tracked
The dashboard visualizes critical advertising metrics, including:

Reach & Engagement: Impressions, Clicks, Shares, Comments, Engagements

Conversion: Purchases

Efficiency Metrics: Click-Through Rate (CTR), Engagement Rate, Conversion Rate, Purchase Rate

Budget: Total Budget, Avg Budget per Campaign

## 💾 Dataset
This analysis is built on four raw CSV files representing a typical advertising database:

campaigns.csv: High-level campaign details (name, budget, duration).

ads.csv: Information about individual ad creatives (platform, type, targeting).

users.csv: Demographic details of users interacting with the ads.

ad_events.csv: Granular log of user interactions (impressions, clicks, shares, purchases) with timestamps.

## 🛠️ Tech Stack
Data Visualization & BI: Microsoft Power BI

Data Source: CSV Files 

## ⚙️ Project Workflow
Data Loading & Transformation: The four CSV files were loaded into Power BI. Data cleaning, transformation (e.g., creating date/time hierarchies, handling data types), and relationship modeling were performed using Power BI's Power Query Editor.

Data Modeling: Relationships were established between the tables (e.g., ad_events to ads, ads to campaigns) based on common keys to enable cross-table analysis.

DAX Calculations: Key Performance Indicators (KPIs) like CTR, Conversion Rate, etc., were custom-calculated using Data Analysis Expressions (DAX) to create new measures.

Dashboard Development: Interactive visualizations (KPI cards, bar charts, line charts, maps, slicers) were built in Power BI's Report View to provide a comprehensive and user-friendly performance tracker.
