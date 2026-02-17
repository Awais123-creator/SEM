# Store Sales: Time Series Forecasting
**Predicting Grocery Sales for Corporación Favorita (Kaggle)**

## Project Overview
This project builds a predictive model to forecast unit sales for thousands of items across different store locations in Ecuador. It demonstrates advanced skills in **Multivariate Time-Series Analysis** and **Relational Data Merging**.

## Live Implementation
You can view and run the full interactive notebook here:
**[View my Notebook on Kaggle](https://www.kaggle.com/code/cheemadata/store-sales-baseline-v1)**

## Technical Solutions
To handle the complexity of retail data, I implemented the following:
* **Relational Data Pipeline:** Integrated 6+ data sources including `oil.csv`, `holidays_events.csv`, and `stores.csv`.
* **The "Lag 16" Strategy:** Engineered a 16-day lag feature to capture the general market mood from the previous cycle, preventing data leakage.
* **Economic Indicators:** Accounted for daily Oil Prices to reflect the macroeconomic health of the local market.
* **Deterministic Seasonality:** Used `CalendarFourier` to model weekly and yearly consumer cycles effectively.

## Tech Stack
- **Python (Pandas, NumPy)** for data manipulation.
- **Statsmodels** for Time-Series Deterministic Processes.
- **Scikit-Learn** for Linear Regression modeling.
