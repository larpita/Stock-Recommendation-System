# Stock-Recommendation-System

## Overview
A rule-based, data-driven stock recommendation system that analyzes a company’s financial strength and long-term performance to generate a Buy / Hold / Sell recommendation.
The system is designed as a decision-support tool using transparent and explainable logic inspired by real-world fundamental analysis.

## Tech Stack
- Python
- Pandas
- NumPy
- yfinance
- Gradio (UI)

## Features
- Accepts a stock ticker as user input
- Fetches real-time market data from Yahoo Finance
- Analyzes:
  - Valuation (P/E Ratio)
  - Profitability (ROE, Profit Margin)
  - Financial risk (Debt-to-Equity)
  - Long-term growth (5-Year CAGR)
- Generates a Buy / Hold / Sell recommendation
- Displays the recommendation, score, and reasoning

## How the System Works
1. User enters a stock ticker.
2. The system fetches five years of historical price data and key fundamentals.
3. Each indicator is evaluated using predefined rules.
4. A score is calculated based on financial health and growth.
5. A final recommendation is generated:
      -BUY → Strong fundamentals and growth
      -HOLD → Moderate performance
      -SELL → Weak fundamentals or low growth
6.The output explains why the recommendation was given.

## Future Enhancements
- Display detailed fundamental metrics (P/E, ROE, Debt-to-Equity, Profit Margin, CAGR) in a structured table for better transparency
- Add support for selecting different markets (NSE, BSE, US) directly from the UI
- Improve scoring logic by incorporating additional indicators such as revenue growth and free cash flow
- Allow comparison of multiple stocks side-by-side
- Extend the system with an optional machine learning model for data-driven recommendation comparison
    
