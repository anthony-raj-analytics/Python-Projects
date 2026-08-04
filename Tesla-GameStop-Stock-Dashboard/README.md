# 📈 Tesla vs GameStop Stock & Revenue Dashboard

A stock analysis project comparing **Tesla (TSLA)** and **GameStop (GME)** historical share price against quarterly revenue, visualized as an interactive dashboard.

## 🎯 Overview

- Extracted historical stock price data using the **yfinance** API
- Extracted quarterly revenue data via **web scraping** (BeautifulSoup)
- Built a dual-panel dashboard for each stock, plotting share price alongside revenue over time

## 📊 Visualizations

| Chart | Insight |
|---|---|
| Tesla dashboard | Historical share price vs. historical revenue |
| GameStop dashboard | Historical share price vs. historical revenue |

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![yfinance](https://img.shields.io/badge/yfinance-blue?style=flat)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-yellow?style=flat)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

## ▶️ How to Run

```bash
pip install yfinance pandas requests bs4 plotly lxml html5lib
jupyter notebook tesla_gamestop_stock_dashboard.ipynb
```

## 📁 Data Source

- Stock price data: Yahoo Finance (via `yfinance`)
- Revenue data: extracted via web scraping from course-provided revenue pages
