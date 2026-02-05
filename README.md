# Trader Performance vs Market Sentiment — Round-0 Assignment

# Overview
This project analyzes how Hyperliquid trader performance is influenced by Bitcoin market sentiment (Fear, Greed, Extreme Greed, Neutral).  
Key metrics analyzed include daily PnL, win rate, trade frequency, leverage, long/short ratio, and trader segmentation.  
The notebook also provides actionable strategies for risk management and performance optimization.

---

#Setup & How to Run

# 1. Clone the Repository
```bash
git clone <https://github.com/anjali-sharma7/Trader_Performance_vs_Sentiment>
cd Trader_Performance_vs_Sentiment
2. Install Dependencies

Make sure you have Python installed. Then install required libraries:

pip install -r requirements.txt
Required libraries include:
pandas
numpy
matplotlib
jupyter

3. Open Notebook
jupyter notebook notebook.ipynb

4. Run Notebook
Open notebook.ipynb in the browser
Click Kernel → Restart & Run All
Ensure all charts and outputs are generated
Files in this Repo

notebook.ipynb — Jupyter Notebook with analysis and insights
README.md — Project overview and instructions
Insights Summary

Fear days have highest PnL and win rate; Neutral days have lowest performance

Traders trade most frequently during Fear sentiment

High-risk traders gain more in Fear but are exposed to higher drawdowns

Frequent traders perform best in Greed; Infrequent traders are more stable

Consistent traders maintain stable performance; inconsistent traders are volatile in Fear

--Actionable Strategy Recommendations
Strategy 1: Sentiment-Aware Leverage Control
Reduce leverage and position size for high-risk traders during Fear & Neutral
Allow higher leverage in Greed regimes

Strategy 2: Trade Frequency Adjustment
Allow higher trade frequency only for frequent, consistent traders in Greed
Restrict trade frequency in Fear and Extreme Greed

Strategy 3 (Optional): Consistency-Based Risk Management
Apply stricter limits or cooldown periods for inconsistent traders during Fear
