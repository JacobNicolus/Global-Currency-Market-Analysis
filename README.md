# 📊 Market Research & Advanced Analytics

### Global Events, Commodities and Currency Markets

**Course Assignment · June 2026**
**Data Source:** [World Bank Commodity Markets (Pink Sheet)](https://www.worldbank.org/en/research/commodity-markets)

An end-to-end market research project analysing how major global events (1960–2026) shaped commodity prices (Brent crude oil, gold, silver) and global currency markets (USD, CNY/RMB), built on World Bank Pink Sheet data.

---

## 📁 Repository Structure

```
├── Report/
│   └── Market_Research_Report.docx
├── Workbook/
│   └── Commodity_Analysis.xlsx
├── Charts/
│   └── 15 individual PNG charts (150 dpi)
└── README.md
```

### 📄 Report

`Market_Research_Report.docx` — Full report (~15+ pages, professional formatting) covering all Part II questions (A1–A4, B5–B8, C9–C12, D13–D16), with all charts embedded, final business recommendations, and a market dashboard.

### 📗 Excel Workbook

`Commodity_Analysis.xlsx` — 10-sheet analytical workbook:

| Sheet | Contents |
|---|---|
| `01_Summary` | Dataset overview and latest vs. average comparison |
| `02_Descriptive Analytics` | High/low prices, top 5 years per commodity |
| `03_Annual Averages` | Full year-by-year price table (1960–2026) |
| `04_Correlation Analysis` | Pearson correlation matrix + regression (B2/B3) |
| `05_Currency Analysis` | SWIFT payment shares, trade finance, offshore RMB |
| `06_Event Timeline` | Complete global event timeline, 1960–2026 (A2) |
| `07_Crisis Comparison` | Indexed price comparison across 3 crises (B8) |
| `08_Volatility Analysis` | Period-by-period volatility statistics |
| `09_Charts` | All 15 charts embedded |
| `10_Recommendations` | Business recommendations (D13–D16) |

### 📈 Charts

15 individual PNG charts at 150 dpi:

| File | Description |
|---|---|
| `chart1_brent_oil_trend.png` | Brent crude with major event markers |
| `chart2_gold_trend.png` | Gold long-term price trend |
| `chart3_silver_trend.png` | Silver peaks and volatility |
| `chart4_gold_silver_combined.png` | Gold vs. Silver (dual axis) |
| `chart5_brent_annual_bar.png` | Brent annual bar chart (2015–2026) |
| `chart6_currency_ranking.png` | Top 10 currencies by global payment share |
| `chart7_offshore_rmb.png` | Offshore RMB by economy (pie chart) |
| `chart8_crisis_comparison_2008.png` | GFC indexed crisis comparison |
| `chart9_volatility_comparison.png` | Monthly % change across 3 commodities |
| `chart10_usd_cny_trend.png` | USD vs. CNY payment share over time |
| `chart11_dashboard.png` | 4-panel market dashboard (dark theme) |
| `chart_B3_correlation_heatmap.png` | Correlation heatmap (seaborn) |
| `chart_B4_gold_silver_scatter.png` | Gold vs. Silver scatter with trendline |
| `chart_B5_gold_moving_avg.png` | Gold with 12-month and 60-month moving averages |
| `chart_B6_brent_forecast.png` | Brent linear trendline forecast (labelled as estimate) |

---

## ❓ Questions Covered

### Part A — Global Events
- **A1** — Three major global events (1973 Oil Crisis, 2008 GFC, 2022 Russia–Ukraine War)
- **A2** — Complete event timeline, 1960–2026 (18 events)
- **A3** — Event most connected to oil (OPEC 1973 / Ukraine 2022)
- **A4** — Event most connected to gold/silver (Nixon Shock / Hunt Brothers)

### Part B — Commodity Analysis
- **B5** — Oil supply shock analysis (4 transmission mechanisms)
- **B6** — Gold during geopolitical uncertainty (safe-haven mechanisms)
- **B7** — Silver: precious metal vs. industrial commodity
- **B8** — Crisis comparison, GFC period (indexed chart + data table)
- **B2** — Correlation table (Pearson r, annual averages)
- **B3** — Correlation heatmap (seaborn)
- **B4** — Gold vs. Silver scatter plot *(bonus)*
- **B5** — Gold moving-average chart *(bonus)*
- **B6** — Brent forecast chart *(bonus — clearly labelled as an estimate, not a prediction)*

### Part C — Currency Markets
- **C9** — USD in global payments (50.49% share analysis)
- **C10** — CNY/RMB role (trade finance 8.30%; offshore RMB 74.55% in Hong Kong)
- **C11** — Sanctions and alternative settlement systems (BRICS Pay)
- **C12** — Offshore RMB financial centres

### Part D — Business Recommendations
- **D13** — Most event-sensitive market
- **D14** — Risk note: oil-exposed company
- **D15** — Risk note: USD/Gold/CNY asset holder
- **D16** — Three practical recommendations

---

## 🛠️ Tools & Technologies

- **Python** — pandas, matplotlib, seaborn (data processing, statistics, visualisation)
- **Microsoft Excel** — multi-sheet analytical workbook
- **Microsoft Word** — final report
- **Data** — World Bank Commodity Markets "Pink Sheet" (monthly & annual series, 1960–2026)

## 📌 Key Highlights

- 66 years of commodity price history analysed (1960–2026)
- 18 major global events mapped to price movements
- Pearson correlation and regression analysis across commodities
- Indexed crisis comparison (1973 Oil Shock · 2008 GFC · 2022 Ukraine War)
- Currency market deep-dive: USD dominance vs. RMB internationalisation

## ⚠️ Disclaimer

This project was produced for academic purposes as part of a Master's course assignment. Forecast charts are simple linear trendline estimates for illustration only and do not constitute financial advice or price predictions.

## 👥 Team

Group project — Master's students, University of Europe for Applied Sciences, Germany

| # | Team Member |
|---|---|
| 1 | **Jacob Nicolus Maggidi** *(Repository Maintainer)* |
| 2 | Isha Soni |
| 3 | Prarthana Puttramegowda |
| 4 | Vijay Mule |
| 5 | Sree Charanya |
| 6 | Praneeth |

---

*Data © World Bank — Commodity Markets (Pink Sheet). Used for educational purposes.*
