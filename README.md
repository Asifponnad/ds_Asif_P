# **Data Science Assignment — Market Sentiment vs Trader Behavior**

## ** Overview**

This project analyzes how trading behavior on Hyperliquid (profitability, leverage, volume, risk) aligns with overall market sentiment measured by the Bitcoin Fear & Greed Index.

The goal is to identify patterns that reveal how sentiment influences trader decisions.

---

## ** Directory Structure**

```
ds_<your_name>/
│
├── notebook_1.ipynb        # Main Colab notebook with full analysis
├── notebook_2.ipynb        # (Optional) Additional notebook
│
├── csv_files/
│   ├── trader_data_small.csv
│   └── fear_greed_index.csv
│
├── outputs/
│   ├── pnl_by_sentiment.png
│   ├── leverage_by_sentiment.png
│   ├── volume_by_sentiment.png
│   └── correlations.png
│
├── ds_report.pdf           # Final report summarizing insights
└── README.md               # This file
```

---

## ** How to Run**

1. Open **Google Colab**
2. Upload:

   * `trader_data_small.csv`
   * `fear_greed_index.csv`
3. Run all cells in `notebook_1.ipynb`
4. Visual outputs will be saved and downloaded for the `outputs/` folder.
5. Export the report as `ds_report.pdf`

---

## ** Analysis Summary**

* Trader aggression increases during **Greed** (higher leverage, larger sizes)
* Trader caution is visible during **Fear** (smaller, safer trades)
* PnL variance increases significantly during Greed
* Volume and risk-taking correlate positively with market sentiment

---

## **🛠 Tech Stack**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## **📄 Author**

Your Name
Data Science Assignment for Web3 Trading Team
