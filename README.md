# BLINKIT-DASHBOARD
Blinkit.PBIT Dashboard 🚀
Interactive Power BI Dashboard designed to analyze Blinkit’s sales performance, customer satisfaction, outlet distribution, and inventory insights.

📌 Overview
Blinkit (formerly Grofers) is a leading Indian quick‑commerce grocery platform. This dashboard provides powerful visuals and insights into Blinkit’s operations across multiple dimensions using KPIs such as Total Sales, Average Sales, Ratings, and more. 


🎯 Business Objectives
Understand how different variables (e.g. fat content, item types, outlet size/location) impact sales and customer behavior

Identify high- and low-performing categories or outlets

Enable data-driven optimization of inventory and delivery strategies

📊 Key KPIs & Visual Insights
KPI	Description	Visualization Type
Total Sales	Overall revenue generated	Donut / Pie Charts
Average Sales	Revenue per transaction	Card / Matrix
Number of Items Sold	Total distinct items sold	Card
Average Customer Rating	Mean rating per item	Card
Sales by Fat Content	Low‑fat vs Regular product revenue	Donut or Stacked Charts
Sales by Item Type	Revenue per product category	Bar Chart
Outlet Sales by Size	Performance based on store footprint	Pie / Donut Chart
Outlet Sales by Location	Tier-wise outlet performance	Funnel Map
Trends by Establishment	Sales vs outlet age over time	Line Chart
Full KPI Matrix by Outlet Type	Multi-dimensional overview	Matrix Card

These visual elements mirror those found in similar Blinkit BI projects. 


🛠️ Tools & Technologies Used
Power BI Desktop (.pbix): Main dashboard file with slicers, bookmarks, and interactive visuals

DAX Measures: Custom KPIs and calculated columns

(Optionally) Python / SQL / Excel: For initial data prep and exploratory analysis, as seen in other Power BI data projects 

🚀 Getting Started
Clone or download the repository

Open the .pbix file using Power BI Desktop (2022/2023 recommended)

Use slicers to filter by outlet type, size, fat content, item category

Interact with bookmarks to toggle between full‑view KPIs and timeline filters

Explore by dashboard sections: sales overview → category breakdown → outlet comparison → geographic trends

🧪 Data Model Summary
Input dataset may include fields like:

Item ID, Fat Content, Item Type, Item Weight, Sales, Rating

Outlet ID, Outlet Size, Location Tier, Year Established

Assumes structured Excel or CSV input—similar format to many Blinkit‐style dashboards 
www.novyPro.com


📁 Repository Structure
bash
Copy
Edit
/blinkit.pbit
│── Blinkit.pbit                   # Power BI project file
│── Data/                          # Optional CSV / Excel datasets
│── Scripts/                       # Optional code (Python/SQL) for EDA or preprocessing
└── README.md                      # This documentation
🔍 Insights & Example Findings
Based on similar projects:

Low‑fat products may outperform regular-fat in sales

Medium‑sized outlets frequently drive higher revenue

Tier‑3 locations sometimes show surprising dominance over urban Tier‑1 outlets

Category-wise, Fruits & Vegetables and Snack Foods often lead in revenue
These trends offer starting hypotheses you can validate with your data
