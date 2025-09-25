# CAPM Calculator 📈

A Streamlit web application for calculating stock beta values and expected returns using the Capital Asset Pricing Model (CAPM).

## Features

- **Multi-stock analysis**: Compare up to 4 stocks simultaneously
- **Beta calculation**: Compute beta values relative to S&P 500
- **Expected return**: Calculate CAPM-based expected returns
- **Interactive charts**: Visualize stock prices and normalized performance
- **Individual stock analysis**: Detailed beta and return analysis for single stocks

## Usage

```bash
streamlit run CAPM_Return.py
```

Select stocks from the dropdown (TSLA, AAPL, NFLX, MGM, MSFT, AMZN, NVDA, GOOGL) and specify the analysis period in years.

## Requirements

- streamlit
- pandas-datareader
- yfinance
- pandas
- plotly
- numpy
