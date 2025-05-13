# 🌤️ Weather Data Analysis – Pune
A data analytics project to explore and visualize weather patterns in Pune, India, over a three-year period (2020–2022). The analysis covers seasonal cycles, daily fluctuations, and interdependencies among temperature, humidity, and precipitation.

## 🔍 Features
- **Seasonal Trends**  
  - Monthly average temperature cycles with clear peaks in April–May and troughs in December–January.  
- **Daily Variability**  
  - Boxplots revealing wider temperature spreads in transitional months (Feb, Oct).  
- **Correlation Analysis**  
  - **Temp vs. Humidity:** –0.62  
  - **Humidity vs. Precipitation:** +0.75  
- **Noise Reduction**  
  - 7-day rolling average smooths daily temperature with a mean absolute error ≈ 1.7 °C.  
- **Time-Series Decomposition**  
  - STL seasonal component remains stable; residuals have a standard deviation ≈ 2.1 °C.

## 🛠 Tools Used
- **Python**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Time Series**: Statsmodels (STL decomposition)


