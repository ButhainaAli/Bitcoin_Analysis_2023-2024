# Bitcoin Data Analysis Project

## Overview
This project analyzes historical Bitcoin (BTC-USD) price and volume data from 2023–2024.
It demonstrates how to use **Python, Pandas, and Seaborn** for data preprocessing, analysis, and visualization.

## Features
* Load and preprocess CSV data
* Explore data: min, max, mean, total trading days
* Date-based filtering (specific dates, months, quarters)
* Boolean indexing and `.query()` for complex conditions
* Multi-condition filters (AND, OR, NOT)
* Monthly analysis and summary statistics
* Challenge tasks:

  * Golden Cross (50-day moving average)
  * Weekend effect analysis (day-of-week patterns)
  * Top & Bottom 10 days by Close price
* Data visualizations:

  * Close price trend
  * High-Low range
  * Close vs Volume scatter plot
  * Monthly summaries and bar plots

## Requirements
* Python 3.8+
* Libraries:

  ```bash
  pandas
  matplotlib
  seaborn
  yfinance
  ```

## Setup
1. Download the dataset CSV file from this link: [bitcoin_price.csv](https://www.bitget.com/price/bitcoin/historical-data)
2. Place the CSV in the `data/` folder of the project.
3. Open the Jupyter Notebook or Python script.
4. Run all cells sequentially to reproduce analysis and plots.

## Usage
* Explore the dataset, filter by date ranges, or analyze specific conditions.
* Modify filters in the code to explore different thresholds or scenarios.
* Visualizations help understand Bitcoin trends and volume patterns.

## Notes
* The code is structured in parts (Part 1–7) for easy step-by-step learning.
* All analysis is reproducible using the provided CSV file or by downloading fresh data via `yfinance`.
