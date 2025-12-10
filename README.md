# 🚕 Uber Trips Analytics Dashboard (Power BI)

## 📌 Overview
This Power BI dashboard provides a comprehensive analysis of Uber trips, focusing on trip volume, customer behavior, time-based trends, and geographic patterns.  
The project demonstrates strong skills in data modeling, DAX, Power Query, and business intelligence storytelling.

## 🎯 Objectives
- Analyze Uber trip demand across different time periods  
- Identify high-traffic hours, days, and locations  
- Evaluate patterns that affect pricing, supply/demand, and driver allocation  
- Build a clean, interactive dashboard for business decision-making  

## 📊 Key KPIs
- **Total Trips**
- **Total Distance Traveled**
- **Average Fare**
- **Trips by Hour**
- **Trips by Location / Pickup Zone**
- **Trips by Category (UberX, Black, Pool, etc.)**
- **Monthly/Weekly Trend**
- **Peak Demand Heatmap**

## 🧩 Dashboard Pages
- **Overview Page** – high-level KPIs & insights  
- **Time Analysis** – hourly, daily, and monthly demand patterns  
- **Geographical View** – trips by pickup/drop-off locations  
- **Category Insights** – ride type performance  

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query**
- **DAX Measures**
- **Data Modeling**
- **CSV / Excel data sources**

## 📂 Repository Structure
├── Project_Uber.pbix
├── data/
│ └── uber_trips.csv
└── images/
└── dashboard_preview.png

## 🧠 DAX Examples
Below are sample DAX measures used in the dashboard:
Total Trips = COUNTROWS(Trips)

Average Fare = AVERAGE(Trips[Fare])

Trips per Hour =
CALCULATE(
COUNTROWS(Trips),
HOUR(Trips[Pickup Time])
)

## 🔍 Insights & Results
- Peak demand occurs during **8:00–10:00** and **17:00–20:00**  
- Weekend trips show a **different demand pattern** compared to weekdays  
- Certain pickup zones consistently outperform others  
- Trip distance correlates strongly with fare, but category changes impact pricing  
- Seasonal trends reveal opportunities for optimized driver allocation  

## 🚀 How to Use
1. Download the `.pbix` file  
2. Open it in **Power BI Desktop**  
3. Refresh data by connecting to the CSV files in the `/data` folder  

## 📧 Contact
Created by **Lazare Tsopurashvili**  
For questions or collaboration opportunities: *lazare.copurashvili@gmail.com*
