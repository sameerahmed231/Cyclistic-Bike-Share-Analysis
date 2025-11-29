# 🚴‍♂️ Cyclistic Bike-Share Analysis — Business Intelligence Project

This repository contains all project files for my Cyclistic Business Intelligence (BI) analysis. The project includes data extraction with SQL, dataset preparation in BigQuery, dashboard development in Tableau, and an executive summary.

---

## 📁 Repository Structure
```
/
├── Project Documentss/
│ ├── Executive_Summary_Presentation.pptx
│ └── (Additional documentation)
│
├── Data/
│ ├── aggregated_citibike_data.sql
│ ├── summer_citibike_data.sql
│ ├── zipcodes.csv
│ └── (Other supporting data files)
│
├── Dashboard/
│ ├── initial_dashboard.twbx
│ └── final_dashboard (to be added later)
│
└── README.md
```

## 📊 Project Overview

The goal of this BI project is to analyze NYC Citi Bike trip patterns and weather conditions to support Cyclistic’s business decisions.  

I merged multiple public datasets in BigQuery, including:  

- NYC Citi Bike Trips  
- Census Bureau US Boundaries (Zip Codes)  
- NOAA GSOD Weather Data  
- Custom Zip Code Mapping Table  

After preparing datasets, I created:  

- An **aggregated dataset** for full analysis  
- A **filtered summer-only dataset** for detailed seasonal insights  
- A **Tableau dashboard** to visualize user behavior, trip duration, location patterns, and weather impact  
- An **executive summary presentation (PPTX)** included in the repository  

The **public Tableau dashboard** can be accessed here: [Cyclistic Bike Share Insights Dashboard](https://public.tableau.com/app/profile/sameer.ahmed2539/viz/CyclisticBikeShareInsightsDashboard/CyclisticBikeShareInsightsDashboard)

---

## 🛠 SQL Queries Used in BigQuery

This project uses two main SQL scripts, located in the `Data/` folder:

**Aggregated Dataset Query**  
- Creates a merged table containing user types, start & end zip codes, boroughs, neighborhoods, weather data, trip durations (grouped in 10-minute intervals), and trip counts.  
- Joins Citi Bike Trips, Zip Code Boundaries, NOAA GSOD Weather, and the Custom Zip Code Mapping Table.

**Summer-Only Dataset Query**  
- Filters trips between July 1 – September 30 (2015) for seasonal analysis.  
- Keeps weather readings, trip duration groups, and all geographic data.

---

## 📈 Tableau Dashboard

The `/Dashboard` directory contains:

- **Book1.twb** — first version (final version will be added later)  

Includes:
- KPIs: Total Trips, Average Duration, Subscriber % 
- Top neighborhoods  
- Trip duration patterns  
- Weather impact  
- Neighborhood/Borough-level trends  

---

## 📝 Methods & Thought Process

- **Aggregated vs. Summer Data**: The aggregated dataset allows overall trends analysis, while the summer dataset focuses on seasonal usage patterns, helping stakeholders identify peak demand periods.  
- **Chart Selection**: Line charts for trends over time, bar charts for total trip minutes, maps for spatial analysis, and KPIs for quick insight were chosen to align with stakeholder goals while keeping the dashboard concise.  
- **Dashboard Design**: Charts were placed to highlight key metrics at a glance, supporting decision-making on user behavior, station demand, and weather impact.  
- **Data Integration**: Combining multiple datasets ensures a holistic view of user behavior, geographic demand, and environmental factors affecting bike usage.

This structure demonstrates the ability to solve real-world BI problems, communicate insights visually, and document workflow for future reference.

---

## 📑 Executive Summary

Find it in:

Project Documentss/Cyclistic Bike Share Project Executive Summary.pptx


This deck presents key findings, visual insights, and recommendations for Cyclistic stakeholders.

---

## 🚀 How to Use

1. Clone or download the repository  
2. Open SQL scripts in BigQuery and upload `zipcodes.csv` before running  
3. Open the Tableau workbook in the `Dashboard/` folder  
4. Review documentation & executive slides in `Project Docs/`

---

## 📬 Contact

For feedback, improvements, or questions about this analysis, feel free to reach out.
