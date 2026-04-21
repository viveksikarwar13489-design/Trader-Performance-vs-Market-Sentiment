## Methodology

Trader transaction data was cleaned and transformed using Python. Exploratory analysis was conducted to compare profitability, win rate, leverage, and behavior across Fear vs Greed sentiment periods.

Machine learning techniques were applied:

- Random Forest for next-day profitability prediction
- K-Means Clustering for trader segmentation

An interactive Streamlit dashboard was developed for business exploration.

---

## Insights

### Sentiment Impact
- Greed sentiment generated stronger trader profitability.
- Fear sentiment increased downside volatility.

### Trader Behavior
- Traders used larger positions during Greed periods.
- High leverage traders were inconsistent.

### Segmentation
Three trader archetypes were identified:

1. Aggressive Speculators
2. Disciplined Winners
3. Casual Traders

---

## Recommendations

1. During Fear markets, automatically reduce leverage and exposure.
2. During Greed markets, scale profitable traders selectively.

---

## Business Value

This framework helps improve capital allocation, trader risk management, and profitability forecasting.
