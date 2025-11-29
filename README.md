# 🚴‍♂️ Cyclistic Bike-Share Analysis — Business Intelligence Project

This repository contains all project files for my Cyclistic Business Intelligence (BI) analysis. The project includes data extraction with SQL, dataset preparation in BigQuery, dashboard development in Tableau, and an executive summary.

---

## 📁 Repository Structure
```
/
├── Project Docs/
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

---

## 📊 Project Overview

This BI project analyzes NYC Citi Bike trip patterns and weather conditions to support Cyclistic’s business decisions.

Datasets used:
- NYC Citi Bike Trips  
- US Census Zip Code Boundaries  
- NOAA GSOD Weather Data  
- Custom Zip Code Mapping Table  

Outputs:
- Aggregated dataset  
- Summer-only dataset  
- Tableau dashboards  
- Executive summary slide deck  

---

## 🛠 SQL Queries

Two SQL scripts in `/Data`:

### 1. Aggregated Dataset Query  
Creates merged trip + weather + zip code summary with:
- usertype  
- start/end zip  
- borough & neighborhood  
- weather metrics  
- 10-minute trip duration bins  
- trip counts  

### 2. Summer-Only Dataset Query  
Filters trips between **July–September 2015** for seasonal behavior analysis.

---

## 📈 Tableau Dashboard

Stored in `/Dashboard`:
- **initial_dashboard.twbx** (final version coming soon)

Includes:
- KPIs  
- Top neighborhoods  
- Trip duration patterns  
- Weather impact  
- Neighborhood/Borough-level trends  

---

## 📑 Executive Summary

Find it in:

Project Docs/Executive_Summary_Presentation.pptx


Contains key findings and recommendations.

---

## 🚀 How to Use

1. Clone or download repository  
2. Run SQL scripts in BigQuery  
3. Upload `zipcodes.csv` before running queries  
4. Open Tableau dashboard  
5. Review executive slides  

---

## 📬 Contact

Feel free to reach out with improvements or questions.
