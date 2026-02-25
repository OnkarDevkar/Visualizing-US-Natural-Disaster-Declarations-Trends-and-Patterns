# Lokesh D

## Basic Information
- **College:** Sri Sairam Engineering College, Chennai
- **Branch:** B.Tech – Artificial Intelligence and Data Science  
- **Year:** Final Year  
- **Batch:** 2022 - 2026  

## GitHub Profile
[GitHub Profile](https://github.com/git-lokesh)

---

# Natural Disaster Analysis  
### Visualizing US Natural Disaster Declarations: Trends and Patterns

## Project Overview
This project is an end-to-end Power BI dashboard analyzing over 70 years of US natural disaster data (1953–2024) sourced from FEMA. The objective was to transform raw disaster declaration records into an interactive analytics solution that visualizes severe weather trends, high-risk geographic regions, and seasonal disaster patterns.

[Repository Link](https://github.com/git-lokesh/NaturalDisasterAnalysis)

---

## Problem Statement
Natural disasters occur frequently across the United States and cause significant impact on lives, infrastructure, and resources. However, raw disaster declaration data is complex and difficult to analyze directly.

This project aims to analyze FEMA disaster declaration data to identify long-term trends, high-risk regions, and dominant disaster types, supporting better preparedness and data-driven planning.

---

## Dataset Description
The dataset is sourced from the FEMA Disaster Declarations dataset and covers records from 1953 to 2024.

It includes:
- Disaster type (Hurricane, Fire, Flood, etc.)
- Affected state and county
- Declaration date
- Incident start and end dates
- Program indicators

The dataset was cleaned and transformed using Power Query before analysis.

---

## Key Features and Technical Work

### Data Engineering
- Cleaned and transformed raw datasets using Power Query  
- Merged state codes with full state names  
- Corrected date hierarchies for accurate time-based analysis  
- Standardized year formats for consistency  

### Time Series Analysis
- Built year-wise trend analysis to detect disaster growth patterns  
- Analyzed seasonal distribution by month  
- Implemented dynamic time filtering  

### Geospatial Analysis
- Implemented filled map visualization  
- Identified high-impact states such as Texas and California  
- Enabled drill-down to state and county level  

### Dashboard Design
- Designed structured layout separating trend and geographic analysis  
- Applied clear KPI structure for executive summary  
- Focused on readability and comparison of disaster categories  

---

## Key Performance Indicators
- **Total Disasters:** Total number of disaster declarations in selected period  
- **Most Impacted State:** State with highest disaster frequency  
- **Peak Year:** Year with maximum declarations  
- **Most Frequent Disaster Category:** Highest occurring disaster type  

---

## Dashboard Structure

### 1. Overview Dashboard
Focuses on time-based and categorical analysis.

Includes:
- Line chart for historical trend analysis  
- Bar chart for monthly seasonality  
- Donut chart for disaster category distribution  
- Global time and category filters  

### 2. Geospatial Risk Analysis
Focuses on geographic concentration and risk.

Includes:
- Filled map highlighting state-wise disaster intensity  
- Drill-down capability for state-level analysis  
- Ranked bar chart for top affected counties  

---

## Key Insights
- Texas and California consistently rank among the most disaster-prone states  
- September is the most active month for disaster declarations  
- Severe Storms and Floods dominate overall disaster frequency  
- Disaster declarations show an upward trend in recent decades  

---

## Recommendations
- Strengthen preparedness in high-frequency states  
- Focus monitoring during peak seasonal months  
- Use historical patterns to support predictive analysis  
- Allocate resources based on dominant disaster types  

---

## Technology Stack
- Power BI  
- Power Query  
- Python (Jupyter Notebook)  
- Git and GitHub  

---

## Skills Gained
- Dashboard development and layout structuring  
- Data modeling using star schema concepts  
- Basic DAX measures and filter context understanding  
- Exploratory data analysis with Python  
- Converting raw datasets into actionable insights  