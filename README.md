# 🌍 Global Disease Outbreak Intelligence Dashboard

An end-to-end data analytics project analyzing COVID-19 outbreak patterns
across 187 countries using Python and Power BI.

---

## 📊 Live Dashboard
> 🔗 [Click here to view the interactive Power BI Dashboard](#)

---

## 🎯 Project Overview

This project takes raw WHO COVID-19 data through a complete analytics pipeline:
- Raw data → Python cleaning → Exploratory analysis → Power BI dashboard

**Dataset:** 49,068 rows across 187 countries from January to July 2020  
**Tools:** Python, Pandas, Matplotlib, Seaborn, Power BI

---

## 🔍 5 Key Insights Discovered

| # | Insight |
|---|---------|
| 1 | 🇺🇸 **Americas** had the highest total case count by July 2020, driven by USA and Brazil |
| 2 | 📈 **Global cases** followed a classic exponential curve, accelerating after WHO pandemic declaration on March 11, 2020 |
| 3 | 🏥 **Europe** had the highest death rate despite fewer cases — pointing to overwhelmed healthcare systems and older demographics |
| 4 | 🌊 **Pandemic wave shifted** — hitting Europe hardest in March-April, then moving to Americas by June-July |
| 5 | ⚠️ **Americas** had the largest gap between active and recovered cases, showing infections were outpacing recoveries |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3 | Data cleaning and analysis |
| Pandas | Data manipulation and aggregation |
| Matplotlib & Seaborn | Data visualization |
| Power BI | Interactive dashboard |

---

## 📁 Project Structure
disease-outbreak-analysis/
│
├── week1_data_cleaning.py       # Data collection and cleaning pipeline
├── week2_analysis.py            # Exploratory analysis and chart generation
├── week3_powerbi_prep.py        # Power BI data preparation and modelling
│
├── who_covid_clean.csv          # Cleaned dataset (49,068 rows x 13 columns)
├── powerbi_country_summary.csv  # Country level summary for map visual
├── powerbi_daily_global.csv     # Daily global timeline for line chart
├── powerbi_region_monthly.csv   # Regional monthly data for heatmap
│
├── chart_top10_countries.png    # Top 10 countries by confirmed cases
├── chart_global_timeline.png    # Global exponential growth curve
├── chart_death_rate_region.png  # Death rate by WHO region
├── chart_heatmap_monthly.png    # Monthly intensity heatmap
└── chart_active_vs_recovered.png # Active vs recovered comparison

---

## 📈 Dashboard Features

- 🗺️ **Interactive world map** — bubble size = case count, color = risk level
- 📈 **Time series chart** — global case growth with WHO declaration marker
- 🎯 **KPI cards** — total confirmed, deaths, recovered, countries affected
- 📊 **Death rate bar chart** — regional comparison
- 🔍 **Cross filtering** — click any visual to filter the entire dashboard

---

## 🖼️ Charts Preview

![Global Timeline](https://github.com/Shikhar336/disease-outbreak-analysis/blob/main/chart_global_timeline.png?raw=true)
![Top 10 Countries](https://github.com/Shikhar336/disease-outbreak-analysis/blob/main/chart_top10_countries.png?raw=true)
![Death Rate](https://github.com/Shikhar336/disease-outbreak-analysis/blob/main/chart_death_rate_region.png?raw=true)
![Heatmap](https://github.com/Shikhar336/disease-outbreak-analysis/blob/main/chart_heatmap_monthly.png?raw=true)
---

## 🗂️ Data Pipeline
Raw WHO Data
↓
Python Cleaning (week1)
↓
Exploratory Analysis (week2)
↓
Power BI Data Prep (week3)
↓
Interactive Dashboard

---

## 👤 Author

**Shikhar**
Aspiring Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](www.linkedin.com/in/shikhar-saraff-204671309)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/Shikhar336)

---

## 📌 How to Run This Project

1. Clone this repository
```bash
git clone https://github.com/Shikhar336/disease-outbreak-analysis.git
```

2. Install required libraries
```bash
pip install pandas matplotlib seaborn requests
```

3. Run the scripts in order
```bash
python week1_data_cleaning.py
python week2_analysis.py
python week3_powerbi_prep.py
```

4. Open `outbreak_dashboard.pbix` in Power BI Desktop

---

*Built as a portfolio project to demonstrate end-to-end data analytics skills*
