# Binance Trade Analysis

## Overview
This project analyzes historical trade data from various Binance accounts over 90 days. The goal is to calculate financial metrics for each account, rank them, and provide a list of the top 20 accounts based on performance.

## Dataset Information
- **Port_IDs:** Unique identifiers for accounts.
- **Trade_History:** Contains details like timestamp, asset, side (BUY/SELL), price, fee, quantity, and realized profit/loss.

## Objectives
- Calculate key financial metrics:
  - ROI (Return on Investment)
  - PnL (Profit and Loss)
  - Sharpe Ratio
  - MDD (Maximum Drawdown)
  - Win Rate
  - Win Positions
  - Total Positions
- Rank accounts based on these metrics.
- Export results and provide visualizations.

## Steps Completed
1. **Data Conversion:** Transformed `Trade_History` into a structured format.
2. **Data Preprocessing:** Cleaned and formatted the dataset.
3. **Feature Engineering:** Calculated essential financial metrics.
4. **Ranking Algorithm:** Developed a scoring system for ranking accounts.
5. **Data Visualization:** Created graphs to visualize key metrics.
6. **Exporting Results:** Saved calculated metrics to a CSV file and printed results.

## Requirements
To run this project, ensure you have the following Python libraries installed:
- pandas
- matplotlib
- numpy

You can install them using pip:
```bash
pip install pandas matplotlib numpy
