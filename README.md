# 🌍 Diseases Attributable to Environment Dashboard (Power BI)

## 📖 Project Overview
This project presents an interactive Power BI dashboard that visualizes the **Burden of Disease Attributable to the Environment (2012)**. The dataset contains country-level estimates of disease burden associated with environmental risk factors. The dashboard enables users to explore patterns across countries, regions, and cause categories through interactive visualizations, slicers, and key performance indicators (KPIs), supporting data-driven public health analysis.

---
 
## ✅ Data Preparation
- **Cleaned and transformed data** using Power Query.  
- **Identified unsupported fields** (such as Age Group analysis).  
- **Removed unnecessary columns** for efficiency.  
- **Handled inconsistent geographic records** to ensure reliable mapping.  

---

## ✅ Data Modeling
- **Troubleshot ambiguous relationship paths** to ensure filters propagate correctly.  
- **Simplified the model** into a cleaner analytical design (star + snowflake schema).  
- Hid unused dimensions (**Dim_GHO**, **Lookup_EnvCauseCode**) and removed disconnected ones (**Dim_AgeGroup**).  

---

## ✅ DAX and Analysis
- **Created measures** for KPIs (TotalBurden, AverageBurden, etc.).  
- **Built KPI cards** for quick insights.  
- **Developed ranking logic** (Top 10 countries, burden rank).  
- **Aggregation logic** for regional and cause breakdowns.  

---

## ✅ Dashboard Development
- **Country analysis** (Top 10 countries, map).  
- **Regional analysis** (burden by WHO region).  
- **Environmental cause analysis** (donut chart by category).  
- **Geographic visualization** (interactive map).  
- **Top 10 analysis** (ranking by burden).  
- **Interactive filtering** (Region and Cause slicers).  
- **Desktop and mobile layouts** for accessibility.  

---

## 📊 Dashboard Features
- **7 KPIs**: Total Burden, Average Burden, Maximum Burden, Minimum Burden, Number of Countries, Number of Environmental Causes, Number of Indicators.  
- **Global Map**: Geographic distribution of burden values.  
- **Top 10 Countries**: Ranked by total burden.  
- **Burden by Region**: Comparative bar chart across WHO regions.  
- **Burden by Cause Category**: Donut chart showing proportions of communicable, noncommunicable, injuries, and other categories.  
- **2 Slicers**: Region and Environmental Cause Category for interactive filtering.  

---

## 📱 Mobile Layout
A mobile‑optimized version of the dashboard was created:  
- KPIs stacked at the top.  
- Map and charts arranged vertically for easy scrolling.  
- Slicers accessible for interactive filtering.  

---

## 📷 Screenshots
- Desktop dashboard view  
- Mobile layout view  
- Interactive demo 
- Model view  


---

## 🚀 How to Use
- Explore screenshots for dashboard layout, model view, mobile design, and interactive view.
- .pbix file available upon request for interview purposes only.

---

## 🔮 Future Work
- **Add age‑disaggregated data** to enable demographic analysis.  
- **Unhide Dim_GHO** for indicator‑specific visuals.  
- **Expand time dimension** if multi‑year data becomes available.  

---

## 💼 Notes for Recruiters/Clients/Users
This project demonstrates:  
- **Data preparation discipline** (cleaning, transformation, handling inconsistencies).  
- **Data modeling expertise** (star + snowflake schema, simplified relationships).  
- **Analytical skill with DAX** (measures, KPIs, ranking logic).  
- **Dashboard design clarity** (country, region, cause analysis).  
- **Professional polish** (desktop + mobile layouts, GitHub documentation).  

---

## 📄 License & Usage Restrictions
Copyright © 2026 HealthAndEcoData. All rights reserved.

This repository is provided for portfolio and demonstration purposes only.

The Power BI dashboard, report design, DAX measures, Power Query transformations, documentation, and other original content in this repository are the intellectual property of the author. No permission is granted to use, copy, modify, reproduce, distribute, or commercially exploit any original content from this repository without the author's prior written permission.

This repository incorporates publicly available data from the World Health Organization (WHO). The original dataset remains the property of its respective owner and is subject to the WHO's terms of use.  

---

## 🤝 Acknowledgments
This project uses publicly available data from the World Health Organization (WHO).

Data Source:

WHO Global Health Observatory – Burden of Disease Attributable to the Environment

The dataset is used solely for educational and portfolio purposes. All rights to the original data remain with the World Health Organization (WHO). The analyses, dashboard design, and visualizations presented in this repository are the author's original work.
