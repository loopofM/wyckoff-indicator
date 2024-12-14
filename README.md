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
- **Risk/Reward Ratio Factor:** Multiplier used to determine potential risk/reward targets for trades.

---

### How to Use:

1. **Understanding the Phases:**
   - The indicator identifies **Accumulation** and **Distribution** phases based on market conditions, helping traders understand market sentiment.
   - **Accumulation** occurs when the market is consolidating with low volatility, indicating potential buying pressure.
   - **Distribution** occurs when the market is showing signs of high volatility and selling pressure.

2. **Key Signals (BC and SC):**
   - The indicator will display labels and visual markers for **Buying Climax (BC)** and **Selling Climax (SC)** events, which may signal a market reversal.
   - **BC** typically occurs at resistance levels with high volume and is associated with a potential sell-off.
   - **SC** typically occurs at support levels with high volume and is associated with a potential rally.

3. **Trend Confirmation (EMA & MTF):**
   - The indicator uses EMAs to filter trades based on the broader market trend, ensuring signals are in the direction of the prevailing trend.
   - **Multi-timeframe (MTF) analysis** provides additional confirmation from higher timeframes.

---

### Example Use Case:

1. If the indicator identifies a **Buy Climax (BC)** at a resistance level with a volume spike, this might suggest a potential reversal to the downside.
2. Conversely, if a **Sell Climax (SC)** is detected at a support level with a volume spike, it may indicate a potential reversal to the upside.

---

### License:

This repository is licensed under the **MIT License**. See [LICENSE](LICENSE) for more details.

---

### Contributing:

Feel free to contribute to this project by opening an issue or submitting a pull request. If you have suggestions or improvements, don’t hesitate to contact me!

---

### Acknowledgments:

- **Pine Script** - For creating the TradingView scripting language used in this project.
- **Wyckoff Theory** - For providing the foundational technical analysis principles behind this indicator.

---

### Contact:

If you have any questions or issues with the script, feel free to contact me via GitHub issues
