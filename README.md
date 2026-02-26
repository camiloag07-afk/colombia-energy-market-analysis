# colombia-energy-market-analysis
Data analysis of spot prices and hydro-reserves in Colombia using Python.

# Colombia Energy Market Analysis: Climate Vulnerability & Spot Prices

# Project Overview
As an Energy Engineer and Data Analyst, I developed this project to quantify the financial impact of climate events (specifically the El Niño Southern Oscillation) on the Colombian wholesale electricity market. Since Colombia's energy matrix is approximately 70% hydroelectric, droughts force the dispatch of expensive thermal generation, causing extreme price volatility.

# Business Objective
To analyze historical spot prices and reservoir levels (2021-2026) to demonstrate the inverse correlation between hydro-reserves depletion and energy price spikes.

# Tools & Technologies
* **Language:** Python
* **Libraries:** Pandas (Data manipulation, merging, cleaning), Matplotlib (Data visualization, dual-axis plotting)
* **Data Source:** XM (Sinergox) - Colombian National Interconnected System Operator via open datasets.

# Key Insights
1. **Perfect Inverse Correlation:** The data reveals a direct and immediate market reaction to water scarcity. 
2. **The 2024 "El Niño" Crisis:** During early 2024, as reservoir levels plummeted near the critical 30% threshold (blue line), the daily weighted average spot price (red line) skyrocketed, peaking above 2,400 COP/kWh.
3. **Market Vulnerability:** This analysis mathematically proves the severe financial exposure of the spot market to climate variability, highlighting the urgent business need to accelerate the integration of non-conventional renewable energy sources (Solar/Wind) to diversify the matrix.
