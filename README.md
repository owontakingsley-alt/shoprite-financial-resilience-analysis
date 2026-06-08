# 🛒 Shoprite Holdings — Financial Resilience Analysis (2016–2025)

> **Business Question:** *How resilient is Shoprite's financial performance during periods of economic downturn in South Africa?*

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-View%20Here-0A7C59?style=for-the-badge&logo=githubpages&logoColor=white)](https://owontakingsley-alt.github.io/bi-project/)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Source-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/excel)
[![World Bank](https://img.shields.io/badge/World%20Bank-GDP%20Data-003087?style=for-the-badge&logo=worldbank&logoColor=white)](https://data.worldbank.org/)

---

## 📌 Project Overview

This project analyses the **financial resilience of Shoprite Holdings** — Africa's largest food retailer — across a decade of economic volatility (2016–2025). Using a combination of company financial data, share price history, and South Africa's macroeconomic indicators, the analysis investigates whether Shoprite's performance tracks the broader economy or operates independently of it.

The findings have practical implications for **investors, analysts, and retail sector strategists** seeking to understand defensive stocks in emerging markets.

---

## 🔑 Key Findings

| Finding | Result | Interpretation |
|---|---|---|
| Revenue vs GDP Growth (Pearson r) | **r = 0.076** | Near-zero correlation — Shoprite is largely insulated from GDP cycles |
| Revenue vs Share Price (Pearson r) | **r = 0.784** | Strong positive relationship — investors closely track financial performance |
| Operating Margin Range | **4.6% – 6.1%** | Stable profitability across the full decade, average 5.59% |
| 2020 Recession Test | GDP −6.17% / Revenue +4.39% | Revenue grew during South Africa's worst modern recession |
| 2026 Revenue Forecast (Linear Regression) | **ZAR 255.77 billion** | Projected continued growth trajectory |
| Supermarket Store Count (2025) | **2,595 (SA) + 268 (Rest of Africa)** | Extensive defensive footprint across the continent |

---

## 📊 Live Interactive Dashboard

🔗 **[Click here to explore the dashboard →](https://owontakingsley-alt.github.io/bi-project/)**

The dashboard includes:
- Revenue trend with 2026 forecast and year-range control
- GDP vs Revenue overlay chart
- Key statistics panel with correlation insights
- Action recommendations based on analysis findings

> *Offline single-file dashboard — no external libraries, no server required.*

---

## 📁 Repository Structure

```
shoprite-financial-resilience-analysis/
│
├── data/
│   ├── sa_gdp_growth.xlsx          # South Africa GDP growth rates (World Bank)
│   ├── shoprite_financials.xlsx    # Revenue, operating profit, margin, store count
│   └── shoprite_share_price.xlsx   # Annual average share price (Investing.com)
│
├── report/
│   └── BI_Final_Report.pdf         # Full academic report with methodology
│
└── README.md
```

---

## 🗂️ Data Sources

| Dataset | Source | Period |
|---|---|---|
| Revenue, Operating Profit, Margin, Store Count | Shoprite Integrated & Annual Reports | 2016–2025 |
| Annual Average Share Price | [Investing.com](https://www.investing.com/) | 2016–2025 |
| South Africa GDP Growth Rate | [World Bank Open Data](https://data.worldbank.org/) | 2016–2024 |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data collection, cleaning, and initial exploration |
| **Python (Pandas, NumPy)** | Statistical analysis — Pearson correlation, linear regression |
| **Matplotlib / Seaborn** | Exploratory data visualisation |
| **HTML / CSS / JavaScript** | Interactive dashboard (vanilla, no frameworks) |
| **GitHub Pages** | Dashboard deployment and hosting |

---

## 📐 Methodology

1. **Data Collection** — Manually compiled from Shoprite's published annual reports (2016–2025), cross-referenced with Investing.com for share price data and World Bank for macroeconomic context.
2. **Correlation Analysis** — Pearson correlation coefficient calculated between: (a) Revenue and GDP growth rate, and (b) Revenue and annual average share price.
3. **Trend Analysis** — Year-on-year revenue growth computed across the full period, including stress-test comparison against the 2020 recession.
4. **Forecasting** — Simple linear regression applied to the revenue time series to produce a 2026 estimate.
5. **Dashboard Development** — Findings visualised in a fully offline, browser-based interactive dashboard deployed via GitHub Pages.

---

## 💡 Business Implications

- **Shoprite exhibits characteristics of a defensive stock** — its revenue growth persisted even when South Africa's GDP contracted sharply in 2020.
- **The near-zero GDP correlation (r = 0.076) suggests** that Shoprite's scale, necessity-based retail model, and geographic diversification protect it from macroeconomic headwinds.
- **The strong revenue-to-share-price correlation (r = 0.784) indicates** that capital markets price Shoprite primarily on its own operational performance, not on macroeconomic sentiment.
- **Stable operating margins (avg. 5.59%)** demonstrate consistent cost discipline over the decade despite inflationary pressures and rand volatility.

---

## 🎓 Academic Context

| | |
|---|---|
| **Student** | Ifeanyi Kingsley Owonta |
| **Student Number** | 24244350 |
| **Programme** | MSc Business Analytics for Decision Makers |
| **Module** | Business Intelligence |

---

## 🏷️ Skills Demonstrated

![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Correlation%20%26%20Regression-0A7C59?style=flat-square)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-Dashboard%20Design-1a6b9e?style=flat-square)
![Financial Analysis](https://img.shields.io/badge/Financial%20Analysis-Retail%20Sector-c0392b?style=flat-square)
![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20NumPy%20%7C%20Matplotlib-3776AB?style=flat-square&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Advanced%20Data%20Handling-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![HTML CSS JS](https://img.shields.io/badge/HTML%20%7C%20CSS%20%7C%20JS-Dashboard%20Development-E44D26?style=flat-square&logo=html5&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployment-181717?style=flat-square&logo=github&logoColor=white)
![Statistical Modelling](https://img.shields.io/badge/Statistical%20Modelling-Pearson%20%7C%20Linear%20Regression-8e44ad?style=flat-square)
![Data Storytelling](https://img.shields.io/badge/Data%20Storytelling-Insight%20Communication-e67e22?style=flat-square)

---

## 📬 Connect

Feel free to reach out or connect on www.linkedin.com/in/ifeanyi-owonta if you'd like to discuss this project or my broader work in business analytics.

---

*Data accurate as of Shoprite's 2025 Annual Report. GDP data sourced from World Bank (2024 latest available at time of analysis).*
