# 🚗 Automobile Sales Dashboard

An interactive web dashboard built with **Dash** and **Plotly Express** to analyze historical automobile sales trends and understand how recession periods impacted vehicle sales.

## 🎯 Overview

The dashboard lets users switch between two views:
- **Recession Period Statistics** — sales trends, vehicle-type performance, advertising spend, and unemployment impact during recession years
- **Yearly Statistics** — sales trends for any selected year, with monthly breakdowns and category-level performance

## 📊 Visualizations

| Chart | Insight |
|---|---|
| Line chart | Average automobile sales fluctuation over recession periods |
| Bar chart | Average vehicles sold by vehicle type |
| Pie chart | Advertising expenditure share by vehicle type |
| Bar chart | Effect of unemployment rate on vehicle type and sales |
| Line chart | Yearly and monthly automobile sales trends |

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=flat&logo=plotly&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

## ▶️ How to Run

```bash
pip install dash pandas plotly
python automobile_sales_dashboard.py
```

Then open `http://127.0.0.1:8050/` in your browser.

## 📁 Data Source

Historical automobile sales dataset (1980–2023) covering sales figures, GDP, unemployment rate, advertising expenditure, and vehicle type across recession and non-recession periods.
