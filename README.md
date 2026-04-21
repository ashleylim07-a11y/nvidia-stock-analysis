# NVIDIA Stock Analysis using Python

## Project Overview
This project analyses NVIDIA’s stock performance using Python. The objective is to understand its price trends, returns, and volatility, and to generate insights useful for beginner investors and finance students.
---
## Problem Statement
The project investigates how NVIDIA’s stock has performed over time and evaluates its risk and return characteristics. It also compares NVIDIA with Apple and the S&P 500 to provide a more meaningful assessment.
---
## Target Audience
This project is intended for beginner investors and finance students who want to understand stock performance and investment risk.
---
## Dataset
The data were obtained from Yahoo Finance using the `yfinance` Python library.
- Stocks analysed: NVIDIA (NVDA), Apple (AAPL)
- Market benchmark: S&P 500 (SPY)
- Data period: 2020–2026
- Access date: 21 April 2026
---
## Methods Used
The following Python techniques were applied:
- Data collection using `yfinance`
- Data cleaning using `pandas`
- Calculation of daily returns
- Volatility measurement using standard deviation
- Data visualisation using `matplotlib`
- Performance comparison using normalized prices
---
## Key Outputs
The project includes:
- NVIDIA price trend chart
- Daily returns (volatility) chart
- Performance comparison chart (NVDA vs AAPL vs S&P 500)
---
## Key Insights
- NVIDIA demonstrates strong price growth over the selected period
- NVIDIA outperforms Apple and the overall market
- The stock shows higher volatility, indicating higher risk
- Growth may be driven by strong demand in AI and technology sectors
---
## Limitations
- The analysis is based only on historical data
- External factors such as economic conditions are not included
- No advanced financial modelling is used
---
## How to Run the Project
1. Install required libraries:
pip install yfinance pandas matplotlib
2. Open the notebook:
nvidia_analysis.ipynb
3. Run all cells

## Project Structure
nvidia-stock-analysis/
│── nvidia_analysis.ipynb
│── README.md
│── requirements.txt
