# Pairs Trading Analysis

This repository contains a Jupyter Notebook for performing pairs trading analysis. Pairs trading is a market-neutral trading strategy that involves matching a long position with a short position in two highly correlated stocks.

## Running the Notebook

To get started with this project, clone the repository and open the Jupyter Notebook in your preferred environment.

1. Clone the github repository
```bash
git clone [https://github.com/coder-ishan/Pairs-Trading-Z-Score]
cd Pairs-Trading-Z-Score
```

2. Open the Jupyter Notebook
```bash
jupyter notebook Pairs_Trading.ipynb
```

### Prerequisites

Ensure you have the following packages installed:
- `numpy`
- `pandas`
- `matplotlib`
- `statsmodels`
- `scikit-learn`
- `yfinance`

You can install these packages using `pip`:

```bash
pip install numpy pandas matplotlib statsmodels scikit-learn yfinance
```

## Notebook Structure

The notebook is organized as follows:

1. **Introduction**: An overview of pairs trading and its significance.
2. **Necessary Imports**: Importing the required libraries and packages.
3. **Data Collection**: Fetching historical price data for the selected pairs.
4. **Data Preprocessing**: Cleaning and preparing the data for analysis.
5. **Visualizing Stock Data**: Visualizing the price data to understand trends and patterns.
6. **Cointegration Test and Z Score**: Testing for cointegration between the pairs and calculating the Z score.
7. **Generate Trading Signals Based on Z Scores**: Creating trading signals based on the Z scores.
8. **Backtesting**: Testing the model on historical data.
9. **Results**: Analyzing the results and performance of the strategy.
10. **Conclusion**: Summarizing the findings and potential improvements.

## Acknowledgements
Data Source: [Yahoo Finance ](https://github.com/ranaroussi/yfinance)
References: [https://www.youtube.com/watch?v=jvZ0vuC9oJk](https://www.youtube.com/watch?v=jvZ0vuC9oJk)
