# Store Sales: Time Series Forecasting
**Predicting Grocery Sales for Corporación Favorita (Kaggle)**
## Project Overview
This project builds a predictive model to forecast unit sales for thousands of items across different store locations in Ecuador. It demonstrates advanced skills in **Multivariate Time-Series Analysis** and **Relational Data Merging**.
## Key Technical Challenges
* **Feature Engineering:** Created time-lag features, rolling window statistics, and extracted date-parts (day of week, month, seasonality).
* **External Regressors:** Merged daily **Oil Prices** (a key economic indicator for Ecuador) and **National/Local Holiday** data to capture sales spikes.
* **Data Scaling:** Handled thousands of product-store combinations using efficient Pandas merging techniques.
* ## Tech Stack
- **Python (Pandas, NumPy)** for data manipulation.
- **Scikit-Learn / XGBoost** for forecasting.
- **Matplotlib/Seaborn** for trend visualization.
- ## 📉 Results
I identified a high correlation between **Promotions** and **Sales volume**, and successfully accounted for the sales dip during specific holiday periods.
