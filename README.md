# Time Series Forecasting for Portfolio Management Optimization

## Project Overview
This project implements advanced time series forecasting techniques to optimize portfolio management strategies for Guide Me in Finance (GMF) Investments. The analysis focuses on three key assets: Tesla (TSLA), Vanguard Total Bond Market ETF (BND), and S&P 500 ETF (SPY).

## Business Objective
GMF Investments is a financial advisory firm specializing in personalized portfolio management. This project aims to leverage cutting-edge forecasting models to predict market trends, optimize asset allocation, and enhance portfolio performance while managing risk.

## Key Components

### 1. Data Extraction and Preprocessing
- Historical financial data from July 2015 to July 2025 using YFinance
- Comprehensive data cleaning and preparation
- Feature engineering for enhanced analysis

### 2. Exploratory Data Analysis
- Analysis of price trends, volatility, and correlations
- Statistical tests for stationarity
- Risk metrics calculation (VaR, Sharpe Ratio)

### 3. Time Series Forecasting Models
- ARIMA/SARIMA implementation for linear forecasting
- LSTM deep learning model for capturing non-linear patterns
- Model comparison and performance evaluation

### 4. Portfolio Optimization
- Implementation of Modern Portfolio Theory
- Efficient Frontier generation
- Identification of optimal portfolios (Maximum Sharpe Ratio & Minimum Volatility)

### 5. Strategy Backtesting
- Performance validation against benchmark portfolio
- Comprehensive risk-return analysis
- Final investment recommendations

## Project Structure
- `portfolio_optimization_analysis.ipynb`: Main Jupyter notebook with complete analysis
- `requirements.txt`: List of required Python packages

## Technologies Used
- Python 3.8+
- Libraries: pandas, numpy, matplotlib, scikit-learn, tensorflow, statsmodels, PyPortfolioOpt

## Installation and Usage
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook portfolio_optimization_analysis.ipynb`

## Key Findings
- Time series forecasting models can effectively capture market trends with reasonable accuracy
- Modern Portfolio Theory successfully identifies optimal asset allocations
- The optimized portfolio strategy generally outperforms traditional allocation approaches
- Tesla's volatility can be effectively balanced with more stable assets like BND and SPY

## Limitations and Future Work
- Expand asset universe to include more diversified holdings
- Explore ensemble forecasting approaches
- Incorporate macroeconomic indicators for enhanced prediction
- Implement dynamic rebalancing strategies

## License
This project is provided for educational purposes only. The forecasting models and investment strategies should not be used for actual trading without professional financial advice.