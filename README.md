![Banner](https://raw.githubusercontent.com/pars1905/tcmb-inflation-analysis/main/banner.png)

# 📈 TCMB Inflation & Exchange Rate Analysis

> Time series analysis of Turkey's CPI, PPI and USD/TRY exchange rate using official Central Bank (TCMB) data.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![pandas](https://img.shields.io/badge/pandas-2.0-150458?logo=pandas) ![matplotlib](https://img.shields.io/badge/matplotlib-visualization-orange) ![Status](https://img.shields.io/badge/status-in%20progress-yellow)

---

## 📌 Project Overview

This project analyzes Turkey's macroeconomic indicators including consumer price index (CPI), producer price index (PPI), and USD/TRY exchange rate fluctuations over time. The goal is to identify trends, correlations, and structural breaks in inflation and currency data using Python-based time series analysis.

**Key Questions:**
- How has Turkey's inflation evolved over the past 10 years?
- What is the correlation between USD/TRY exchange rate and CPI?
- Can we identify structural break points in inflation trends?

---

## 📂 Dataset

| Source | Description | Access |
|---|---|---|
| [TCMB EVDS](https://evds2.tcmb.gov.tr) | Official Central Bank data portal | Free / API |
| CPI (TÜFE) | Monthly consumer price index | TCMB EVDS |
| PPI (ÜFE) | Monthly producer price index | TCMB EVDS |
| USD/TRY | Daily exchange rate | TCMB EVDS |

---

## 🛠️ Tools & Libraries

- **Python 3.10**
- **pandas** — data cleaning & transformation
- **matplotlib / seaborn** — visualization
- **numpy** — statistical calculations
- **statsmodels** — time series decomposition

---

## 📊 Analysis Steps

1. Data extraction from TCMB EVDS (CSV download / API)
2. Data cleaning and datetime indexing
3. Trend visualization — CPI, PPI, USD/TRY over time
4. Correlation analysis between exchange rate and inflation
5. Rolling average and seasonal decomposition
6. Key findings and interpretation

---

## 📁 Repository Structure

```
tcmb-inflation-analysis/
├── data/
│   ├── raw/          # Original TCMB CSV files
│   └── processed/    # Cleaned datasets
├── notebooks/
│   └── analysis.ipynb
├── visuals/          # Output charts and graphs
├── banner.png
└── README.md
```

---

## 🔍 Key Findings

> 🚧 Analysis in progress — findings will be updated upon completion.

---

## 👤 Author

**Osman Manay** — Applied Economist & Data Analyst  
[LinkedIn](https://linkedin.com/in/osman-manay-48b3171ba) · [GitHub](https://github.com/pars1905)

---

*Data source: Republic of Turkey Central Bank (TCMB) — Electronic Data Delivery System (EVDS)*
