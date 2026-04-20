# High-Frequency Microstructure Analysis of Bitcoin Trading

# Overview
This project analyzes tick-level Bitcoin (XBTUSD) trading data to study market microstructure dynamics under event-driven conditions.
The focus is on how liquidity, volatility, and informed trading behavior evolve during periods of heightened uncertainty, specifically around the U.S. Election Day.

# Objectives
Quantify liquidity dynamics using bid–ask spread measures
Estimate informed trading intensity using the PIN model
Analyze volatility structure using Roll model and realized volatility
Detect structural shifts in market behavior during event-driven regimes

# Data
Source: BitMEX high-frequency trade and quote data
Asset: XBTUSD (Bitcoin perpetual futures)
Frequency: Tick-level (~70K–90K trades per day)
Period:
November 4, 2024 (Pre-election)
November 5, 2024 (Election Day)

# Methodology
1. Liquidity Measures
Quoted Spread
Effective Spread
Realized Spread
2. Volatility Estimation
Roll Model (microstructure-based volatility)
Realized Volatility
Intra-day volatility patterns
3. Market Microstructure Modeling
PIN (Probability of Informed Trading)
Trade direction classification
Order flow dynamics

# Key Findings
Increase in informed trading: PIN rose from ~18% to ~26% on election day
Spread compression: Improved liquidity and tighter bid–ask spreads
Higher trading intensity: Increased volume and market participation
Regime shift: Transition toward more information-driven trading behavior
🧠 Insights
Event-driven markets exhibit enhanced price discovery efficiency
Higher informed trading activity suggests information asymmetry during macro events
Liquidity and volatility are strongly linked to trading intensity and market sentiment
# Tech Stack
Python / R
Libraries: pandas, numpy, highfrequency, data.table
Statistical methods: Time series analysis, microstructure modeling

# How to Run
Clone the repository:
git clone https://github.com/yourusername/bitcoin-microstructure-analysis.git
Install dependencies:
pip install -r requirements.txt
Run analysis scripts or notebooks
# Future Work
Extend analysis to multiple crypto assets
Incorporate order book depth and imbalance metrics
Develop predictive models for short-term price movements

👤 Author
Mohammad Shipon
MS Financial Engineering, Stevens Institute of Technology
