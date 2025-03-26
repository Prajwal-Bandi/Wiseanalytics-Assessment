# Sales Forecasting Project

## Overview

##

This project aims to predict future sales using various machine learning models, including Naïve Forecasting, ARIMA, Random Forest, XGBoost, and LSTM. The dataset includes information on store sales, oil prices, holidays, and transactions.

## Requirements

Ensure you have the following dependencies installed:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn statsmodels xgboost tensorflow missingno
```

## Dataset

- `train.csv`: Historical sales data
- `test.csv`: Test data for predictions
- `stores.csv`: Store details
- `oil.csv`: Oil price data
- `holidays_events.csv`: Holiday and event data
- `transactions.csv`: Store transaction data

## Running the Project

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd sales-forecasting
   ```

2. Place the dataset files in the project directory.

3. Run the Python script:


## Models Used

- **Naïve Forecasting**: Baseline model
- **ARIMA**: Time series model
- **Random Forest**: Tree-based regression
- **XGBoost**: Gradient boosting model (Best performer)
- **LSTM**: Deep learning-based approach

## Evaluation Metrics

- **RMSE**: Measures the error in predictions
- **MAPE**: Percentage error in predictions
- **R-squared**: Measures model performance

## Results

XGBoost provided the best performance with the lowest error rates and highest accuracy.

## Business Insights

- Consider inventory optimization based on forecasted demand.
- Use promotions strategically to maximize sales.
- Monitor external factors like oil prices and holidays for better planning.

## Future Improvements

- Fine-tune hyperparameters for better accuracy.
- Incorporate additional external factors such as weather data.
- Experiment with ensemble learning techniques.

## Author

[Prajwal Bandi](https://github.com/PrajwalBandi)

