# Intrinsic-value-calculator
A Streamlit application which estimates the intrinsic value of stocks using DCF model and Graham valuation. It retrieves financial data from Yahoo Finance and provides an easy way to analyze a company's fair value.
# Intrinsic Value Calculator

A simple Streamlit application that estimates a company's intrinsic value using the Discounted Cash Flow (DCF) method. The app retrieves financial data from Yahoo Finance and provides a quick valuation based on user-defined assumptions.

## Features

- Fetches company financial data automatically
- DCF-based intrinsic value calculation
- Adjustable discount rate, growth rate, and terminal growth rate
- Option to use custom or historical Free Cash Flow
- Revenue and cash flow forecast charts
- Basic Graham valuation estimate

## Installation

```bash
git clone https://github.com/yourusername/intrinsic-value-calculator.git
cd intrinsic-value-calculator
pip install -r requirements.txt
streamlit run app.py
```

## Tech Stack

- Python
- Streamlit
- yfinance
- Pandas
- NumPy

