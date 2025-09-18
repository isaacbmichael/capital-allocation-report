# Strategic Capital Allocation – Monte Carlo Simulation

This project evaluates long-term investment outcomes across **AI, Crypto, and Benchmark strategies**, comparing **Fixed vs Rebalanced** allocations.  
It generates **executive-level HTML & PDF reports** with Monte Carlo simulations, summary tables, and visualizations.

> **Assumptions (current run):** Initial capital = **$100,000** • Horizon = **20 years** • Daily returns **2015–2025** • N = *configurable* • Rebalancing cadences: **Monthly / Quarterly / Semi-Annual / Annual**

---

## ✨ Features
- Monte Carlo simulation of **20-year outcomes** using real daily returns (2015–2025).
- Portfolio strategies include:
  - **100% BTC**, **100% XRP**  
  - **AI Blend** (NVDA, MSFT, GOOGL, AAPL, TSLA)  
  - **Crypto Blend** (BTC + XRP)  
  - **Mixed AI/Crypto** allocations (e.g., 60/40, 70/30)  
  - **Benchmark** allocations (VOO, SPY, S&P 500)  
  - **CFO Policy** (conditional BTC/AI exposure if benchmark > 8%)  
- Comparison of **Fixed** vs **Rebalanced** (Monthly / Quarterly / Semi-Annual / Annual).
- Executive-style report includes:
  - **Executive Summary**  
  - **Distribution of Outcomes** (log-scale chart)  
  - **Conclusions & Recommendations**  
  - **Methodology, Asset Universe, Strategy Definitions**
- Outputs both **interactive HTML** and **ready-to-share PDF** reports.

---

## 📌 Latest Highlights (2025-09-18)
*(Selected medians from the current export; see report for full table & percentiles.)*
- **100% BTC (Fixed)** – Median terminal value ≈ **$261M**
- **60% Crypto / 40% AI (Semi-Annual)** – Median ≈ **$126M**
- **100% VOO (Annual)** – Median ≈ **$547k**

---

## 📊 Example Outputs
- **[View HTML Report](./capital_allocation_report.html)**  
- **[Download PDF Report](./capital_allocation_report.pdf)**  

> Tip: The distribution chart uses a **log-scale x-axis** to show tail behavior across strategies.

---

## 🚀 Run in Google Colab
You can run this notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isaacbmichael/<your-repo-name>/blob/main/Capital_Allocation_MonteCarlo.ipynb)

---

## 📂 Repository Contents
- `Capital_Allocation_MonteCarlo.ipynb` – Main notebook (Colab-compatible).  
- `capital_allocation_report.html` – Executive HTML report.  
- `capital_allocation_summary.csv` – Summary table of results.  
- `capital_allocation_distribution.png` – Distribution chart (log scale).
- _(Optional)_ `capital_allocation_report.pdf` – Executive PDF report.  

---

## 🧭 Glossary
- **Fixed vs Rebalanced:** Fixed holds allocations constant from day 0; Rebalanced restores target weights on a schedule.  
- **Percentiles (5th / 50th / 95th):** Terminal value distribution cut-points across simulations, indicating downside/typical/upside outcomes.  
- **CFO Policy (Target 8%):** Conditional BTC/AI exposure only when the benchmark exceeds an 8% threshold (configurable).

---

## ⚠️ Disclaimer
This project is for **educational and demonstration purposes only**.  
It does not constitute financial advice. Past performance is not indicative of future results.

---

© 2025 Isaac B. Michael • [Email](mailto:isaac.b.michael@gmail.com) • [LinkedIn](https://www.linkedin.com/in/isaacbmichael) • [GitHub](https://github.com/isaacbmichael)
