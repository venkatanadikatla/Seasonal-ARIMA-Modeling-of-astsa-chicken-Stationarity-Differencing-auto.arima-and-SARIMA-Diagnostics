# Seasonal-ARIMA-Modeling-of-astsa-chicken-Stationarity-Differencing-auto.arima-and-SARIMA-Diagnostics
Quick EDA, ADF stationarity testing, log transform + seasonal differencing (lag 12), ACF/PACF inspection
# Seasonal ARIMA Modeling of `astsa::chicken`
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](<<ADD_YOUR_NOTEBOOK_URL>>)

This notebook analyzes the monthly **`chicken`** time series from `astsa`:
- **EDA**: trend/seasonality, summary stats
- **Stationarity**: ADF tests (ct, c, nc)
- **Transforms**: log + seasonal differencing (lag = 12)
- **Identification**: ACF/PACF (seasonal & nonseasonal cues)
- **Selection**: `forecast::auto.arima` with/without approximation
- **Estimation/Diagnostics**: `astsa::sarima` fits, residual ACF, Q–Q, Ljung–Box
- **Recommendation**: pick lowest AIC/AICc with clean residuals
