# Trader Behavior Insights – Junior Data Scientist Assignment

## Overview

This repository contains my submission for the **Trader Behavior Insights** assignment as part of the hiring process for the **Junior Data Scientist** position at PrimeTrade.  

The goal of the assignment is to explore the relationship between **trader performance** and **Bitcoin market sentiment**, uncover hidden patterns, and deliver insights that can drive smarter trading strategies.

---

## Datasets Used

1. **Historical Trader Data (Hyperliquid)**  
   - Columns: `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Size USD`, `Side`, `Timestamp IST`, `Start Position`, `Direction`, `Closed PnL`, `Transaction Hash`, `Order ID`, `Crossed`, `Fee`, `Trade ID`, `Timestamp`  
   - Contains trader-level information about executed trades, PnL, trade sizes, and leverage.

2. **Bitcoin Fear & Greed Index**  
   - Columns: `timestamp`, `value`, `classification`, `date`  
   - Indicates Bitcoin market sentiment on a scale of Fear to Greed.

---

## Objective

- Analyze how **market sentiment** (Fear/Greed) affects trader behavior and profitability.  
- Identify patterns in trader **profit/loss**, **trade sizes**, and **leverage** with respect to market sentiment.  
- Generate visualizations to illustrate insights.  

---

## Key Analysis & Visualizations

1. **Trader Profitability vs Market Sentiment**  
   - Boxplots of trader PnL grouped by market sentiment.  
   - Insight: How different market conditions influence profitability.

2. **Trade Size vs Market Sentiment**  
   - Boxplots and barplots of `Size USD` grouped by sentiment.  
   - Insight: Traders may take larger positions in certain market conditions (proxy for leverage).

3. **Leverage / Exposure Analysis**  
   - Average exposure analyzed by sentiment.  
   - Insight: Patterns of risk-taking in different market moods.

---

## Files

- `TraderBehaviorInsights.ipynb` – Jupyter Notebook containing the full analysis, visualizations, and insights.  
- `README.md` – This file.  

---


