# Smart Agriculture Crop Monitoring and Yield Optimization

An Excel-based data analysis project exploring how soil, weather, and irrigation conditions affect crop yield — using Pivot Tables, Pivot Charts, and an interactive dashboard.

## 📌 Project Overview

This project analyzes a Smart Agriculture dataset to understand what drives crop yield across different farms, regions, and growing conditions. The goal is to turn raw agricultural data into clear, actionable insights using Excel's analytical tools.

## 📊 Dataset

- **Records:** 200
- **Columns:** 13
- **Fields include:** Farm ID, Crop Type, Region, Soil Type, Sowing/Harvest Dates, Soil Moisture (%), Rainfall (mm), Temperature (°C), Fertilizer Used (kg), Irrigation Type, Pest Incidence Level, Crop Yield (kg)

Data was collected from multiple farms and includes a mix of integer, float, date, and string data types.

**Data Cleaning:** Duplicate records were removed, missing values handled, date formats corrected, and data types validated before analysis.

## 🎯 Objectives

1. **O1:** Analyze crop yield based on soil and weather conditions
2. **O2:** Study the impact of soil moisture, rainfall, and temperature on crop yield
3. **O3:** Analyze and compare agricultural productivity across different regions

## 🔍 Approach

Each objective was tackled using Pivot Tables and Pivot Charts:

| Objective | Chart Type | Approach |
|-----------|-----------|----------|
| O1 | Combo Charts | Pivot-based crop yield analysis (yield vs. soil moisture, crop-wise distribution) |
| O2 | Column Charts | Soil & weather impact analysis (moisture, rainfall, temperature vs. yield) |
| O3 | Column/Bar Charts | Regional & irrigation comparison |

## 📈 Key Insights

- **Region:** North region shows the highest crop productivity (avg. yield ~3,232 kg)
- **Soil Moisture:** Moderate soil moisture levels correspond to higher crop yield
- **Rainfall:** Optimal (moderate) rainfall increases crop yield — both excessive and low rainfall reduce it
- **Irrigation:** Drip irrigation produces the highest average yield (~2,878 kg), followed by Canal (~3,016 kg)
- **Overall stats:** Average yield of 2,616 kg per farm, ranging from 519 kg to 4,998 kg, across a total yield of 563,204 kg

## 📁 Repository Structure

```
Smart_Agriculture_Crop_Monitoring/
├── Dataset/          # Raw and cleaned dataset (.xlsx)
├── Report/           # Project documentation and written analysis
├── Screenshot/       # Dashboard and chart screenshots
└── README.md
```

## 🖥️ Dashboard

The interactive dashboard includes:
- KPI metrics (Average, Max, Min, and Total Yield; Avg Rainfall, Soil Moisture, Temperature)
- Crop Yield vs. Soil Moisture / Rainfall (by crop type)
- Region-wise average crop yield
- Soil moisture and rainfall vs. yield breakdowns
- Irrigation method comparison
- Interactive slicers for Crop Type, Region, Soil Type, and Irrigation Type

## 🛠️ Tools Used

- Microsoft Excel (Pivot Tables, Pivot Charts, Dashboard, Slicers)

## 👤 Author

**Vaibhav Satish Wairkar**
