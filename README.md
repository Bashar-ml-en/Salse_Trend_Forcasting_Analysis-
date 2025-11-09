🧠 Sales Trend & Forecast (ARIMA)

📘 Summary

This project dives into a small daily sales dataset to uncover patterns, price sensitivity, and forecast future demand using ARIMA modeling.

📊 Highlights

Weekly Seasonality: Clear repeating sales cycles with steady growth.
Price Elasticity: Demand is price inelastic (≈ 0.28) — customers aren’t very reactive to price changes
Forecasting: ARIMA(1,1,1) predicts stable sales growth over the next year. 

📈 Visuals

Rolling average trend
<img width="576" height="362" alt="comprison" src="https://github.com/user-attachments/assets/3dfd5aee-2e84-4423-a1ef-0a328cefb297" />

Weekly heatmap
<img width="576" height="351" alt="heatmap" src="https://github.com/user-attachments/assets/f6cc15e8-60c8-4ed6-ad53-856cf5d85913" />

ARIMA forecast
![forcasting for 6  monthes forward](https://github.com/user-attachments/assets/d12edf77-7231-4457-9f1d-5e284686e332)

Log-log regression for elasticity
<img width="576" height="376" alt="%of chngs in sales" src="https://github.com/user-attachments/assets/167da07d-9f1f-4138-ac99-2adf933f7faf" />


🧰 Tools

Python • pandas • matplotlib • statsmodels • scikit-learn

📎 Dataset

Mock file (mock_kaggle.csv) with:
data: date
venda: sales
estoque: stock
preco: price

🏁 Takeaway

Even small datasets can reveal big insights — from pricing strategy to demand forecasting.
