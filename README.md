📊 Sentiment vs Trader Behavior Analysis

Objective

The objective of this project is to analyze how market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid. The goal is to identify patterns that can help design smarter trading strategies.

---

📂 Dataset

This project uses two datasets:

1. **Bitcoin Market Sentiment (Fear/Greed)**

   * Columns: date, classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)

2. **Hyperliquid Historical Trader Data**

   * Includes: account, side, size_usd, timestamp, closed_pnl, etc.

---

⚙️ Setup

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

▶️ How to Run

1. Open the project in VS Code
2. Navigate to:

   ```
   notebooks/analysis.ipynb
   ```
3. Run all cells using **Run All**

Outputs will be generated in:

```
notebooks/outputs/
```

---

📊 Key Insights

* **Extreme Greed shows the highest profitability and win rate**

  * Indicates strong momentum-driven trading opportunities

* **Fear markets outperform normal Greed conditions**

  * Suggests better entry points during pessimistic phases

* **Trader behavior changes with sentiment**

  * Larger trade sizes observed during Greed phases
  * Increased activity indicates higher risk-taking behavior

---

🚀 Strategies

* **Trend-following in Extreme Greed**

  * Increase exposure to capture momentum-based gains

* **Controlled dip-buying in Fear markets**

  * Enter positions cautiously with disciplined sizing

* **Avoid overtrading during normal Greed**

  * Lower performance suggests inefficient trading behavior

---

📁 Outputs

Generated outputs include:

Charts

* `pnl_vs_sentiment.png`
* `pnl_vs_sentiment_clean.png`
* `pnl_bar.png`
* `winrate.png`
* `size_behavior.png`

Tables

* `pnl_summary.csv`
* `winrate_summary.csv`

---

🧠 Notes

* Zero PnL trades were removed to ensure meaningful performance analysis
* Outliers were filtered in visualizations for clarity, while full data was used for analysis

---
