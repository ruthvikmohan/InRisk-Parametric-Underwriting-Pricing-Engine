# 🎛️ InRisk Parametric Underwriting & Pricing Engine

An institutional-grade parametric insurance backtesting and pricing engine engineered to underwrite solar generation deficit risks. This project translates quantitative finance methodologies into production-ready climate insurtech infrastructure.

## 🚀 Core Architecture

- **Mathematical Engine:** Translates traditional asset return math (GARCH/Value-at-Risk concepts) into physical environmental space using **Surface Solar Radiation Downwards (SSRD)** data.
- **Actuarial Modeling:** Automates historical Burn Cost calculations and applies customized risk loading buffers to output commercial insurance premiums.
- **Interactive UI Terminal:** Built with Streamlit and Plotly to enable underwriters to stress-test trigger thresholds and review historical payout audit trails dynamically.

## 📊 Technical Parameters

- **Asset Baseline ($P50$):** 4,600 kWh/year
- **System Constraints:** Capacity: 3.0 kVA | Performance Ratio ($PR$): 0.80
- **Strike Level Threshold:** Adjustable (Default: 90% of $P50$ Baseline)
- **Max Financial Exposure:** ₹26,450.00 (Fully Capped Loss Protection)

## 🛠️ Installation & Reproduction

```bash
# Clone the repository
git clone https://github.com
cd InRisk-Parametric-Underwriting-Pricing-Engine


# Install required dependencies
pip install streamlit pandas numpy scipy plotly pyngrok

# Execute the local dashboard deployment instance
streamlit run app.py
```
