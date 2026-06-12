# Bitcoin Sentiment & Trader Performance Analysis
### Primetrade.ai Data Science Assessment

---

## Overview

This project explores the relationship between **Bitcoin market sentiment** (Fear & Greed Index) and **trader performance** on Hyperliquid — a decentralized perpetuals exchange. The goal is to uncover hidden patterns and deliver actionable trading strategies.

---

## Datasets

| Dataset | Records | Period |
|---|---|---|
| Hyperliquid Historical Trader Data | 211,218 trades | May 2023 – May 2025 |
| Bitcoin Fear & Greed Index | 2,644 days | Feb 2018 – May 2025 |

---

## Key Findings

- **Extreme Greed** yields the highest avg PnL ($67.89) and win rate (46.5%)
- **Fear days** see the largest position sizes ($7,816 avg) — traders buy the dip
- **Sentiment lag effect**: previous day's Greed predicts higher next-day PnL than same-day Greed
- **Trader clustering** reveals 3 profiles: High Value, High Frequency, and Mid Tier — each thrives in different sentiment regimes
- **Coin rotation**: HYPE dominates Fear, @107 spikes in Extreme Greed, SOL peaks in Greed/Neutral

---

## Actionable Strategies

1. **Contrarian Accumulation** — size up in Fear, reduce in Greed
2. **Lag-Based Entry Signal** — use yesterday's sentiment as a next-day trigger
3. **Coin Rotation by Regime** — match coin selection to current sentiment
4. **Trader-Type Alignment** — tailor strategy to your trading profile

---

## Repository Structure

```
├── primetrade-sentiment-analysis.ipynb   # Full analysis notebook
├── Primetrade_Analysis_Report.docx       # Insights report with tables & strategies
├── README.md
└── .gitignore
```

---

## Tools Used

- Python (pandas, matplotlib, seaborn, scikit-learn)
- Kaggle Notebooks
- KMeans Clustering
- Fear & Greed Index API data

---

## Author

**Aditya Suhas Bandi**  
Data Science Candidate — Primetrade.ai Assessment | June 2025
