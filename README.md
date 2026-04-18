# personal-finance-dashboard
 A Streamlit web app that analyzes your stock portfolio and gives actionable insights.

## What it does
- Analyze multi-stock portfolio performance
- Compare against NIFTY 50 benchmark
- Show risk level (volatility) and diversification
- Generate text insights on portfolio health

## Features
- Multi-stock input (comma separated)
- Correlation heatmap
- Portfolio vs benchmark comparison
- Risk classification (Low/Medium/High)
- Diversification insights

## How to run
pip install -r requirements.txt
streamlit run app.py

## Key concepts used
- Price normalization (base 100)
- Correlation analysis
- Volatility estimation
- Equal-weight portfolio assumption
