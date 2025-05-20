# scikit-learn-stock-pipeline

# Time-Aware Stock Price Prediction

This project builds a machine learning pipeline to forecast next-day stock closing prices using a time-aware modeling approach. Leveraging `RandomForestRegressor` and `scikit-learn` pipelines, the model integrates advanced feature engineering — including lagged closing prices, rolling volatility, and percentage returns — to capture temporal patterns in market behavior.

Additionally, the model incorporates S&P 500 index data to provide broader market context and improve predictive performance. Hyperparameter optimization is conducted using `GridSearchCV`, and model evaluation is based on RMSE and R² metrics.

---

## Features

- Time-series aware data preparation
- Lag features, rolling statistics, and return-based indicators
- Integration of market index (S&P 500) data
- Implemented pipelines
- Model tuning using `GridSearchCV`
- Performance evaluation using RMSE and R²
- Visualizations for actual vs predicted prices

---

## Technologies Used

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/time-aware-stock-prediction.git
   cd time-aware-stock-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook to explore and train the model:
   - `stock_price_prediction.ipynb`

---

## Example Output

Sample metrics:
- RMSE: ~1.94
- R² Score: ~0.38

![Prediction vs Actual](assets/prediction_plot.png)

---

## Insights

- Lag features and short-term moving averages contributed significantly to model performance.
- External S&P 500 index features improved context awareness during volatile market conditions.
- Volatility and returns added predictive value during trend reversals.

---

## Contact

For questions or collaboration:
**Shrish Sharma** – [LinkedIn](https://linkedin.com/in/shrihs-sharmaa) – shrish.36.sharma@gmail.com

---

> Built as part of a personal machine learning portfolio to explore time-series modeling and applied feature engineering for financial data.
