
# 📊 Manufacturing Quality Dashboard (Power BI)

## 🔍 Project Overview
This project focuses on analyzing manufacturing production and rejection data using Power BI.  
The goal is to identify key quality issues, track performance metrics, and support data-driven decision-making.

---

## 🚀 Key Features
- 📌 KPI Tracking (Total Production, Rejection %, Rework %, Quality Cost)
- 📈 Trend Analysis of rejected quantity over time
- 📊 Defect Analysis by type, location, and part
- 🧠 Pareto Analysis to identify major defect contributors
- 🎯 Interactive dashboard with slicers and filters

---

## 🛠 Tools & Technologies
- Power BI
- Excel / CSV Files
- Data Modeling (Star Schema)
- DAX (for calculated measures)

---

## 🗂 Data Model
The project uses a **star schema** with:

### Fact Tables:
- FACT_Production
- FACT_Rejection

### Dimension Tables:
- DIM_Part
- DIM_Machine
- DIM_Operator
- DIM_Supplier
- DIM_Date

---

## 📊 Dashboard Insights
- Identified top defect types contributing to maximum rejection
- Highlighted defect-prone areas (Surface, Center, Edge)
- Monitored rejection trends over time
- Evaluated quality cost impact on production

---

## 📸 Dashboard Preview

![Dashboard](https://raw.githubusercontent.com/Nitishkumar50814/Power-Bi-Project/main/Quality-dashboard-PowerBI-Dashboard/Dashboard_Screenshort/Executive%20Overview.png)]

---

## 📂 Project Structure
-
Quality-Dashboard-Project/
│
├── Dashboard.pbix
├── data/
├── screenshots/
└── README.md
