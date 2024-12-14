# Wyckoff Indicator V3 (Refined)

This repository contains the **Wyckoff Indicator V3 (Refined)** Pine Script, a technical analysis tool designed for traders to identify key Wyckoff phases in the market, including Accumulation and Distribution phases, as well as detecting Buy Climax (BC) and Sell Climax (SC) events.

### Features:
- Identifies Wyckoff Accumulation and Distribution phases based on market conditions.
- Detects **Buying Climax (BC)** and **Selling Climax (SC)** events, which are key signals for potential market reversals.
- Includes trend filters based on Exponential Moving Averages (EMA) to confirm the broader market trend.
- Volume analysis for detecting **Volume Spikes** that are associated with key market events.
- Multi-timeframe (MTF) analysis for confirming trends across different timeframes.
- Visual aids for BC and SC, with labels and plots for easy interpretation.

---

### Installation:

1. **Create a TradingView account** (if you don't already have one) at [TradingView](https://www.tradingview.com/).

2. **Add the script to TradingView:**
    - Open the **Pine Script editor** on TradingView.
    - Copy and paste the entire code from `wyckoff_indicator_v3.pinescript` into the editor.
    - Save the script by clicking **Save** and providing a name for it (e.g., **Wyckoff Indicator V3**).
    - Add the script to your chart by clicking **Add to Chart**.

---

### Parameters:

- **Swing Length for Accumulation/Distribution Detection:** Determines the look-back period for identifying Accumulation/Distribution.
- **Volume Moving Average Length:** Length of the moving average for volume analysis.
- **Volume Spike Multiplier:** Multiplier to detect significant volume spikes.
- **ATR Length:** Length for calculating Average True Range (ATR) to define volatility-based zones.
- **EMA Length:** Period for calculating the trend confirmation Exponential Moving Average (EMA).
- **Minimum Event Spacing (Bars):** Defines the minimum number of bars between detected events to avoid overlap.
- **
