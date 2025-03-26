# Sales Forecasting Project

## Project Overview
This project focuses on forecasting sales using multiple models, including traditional statistical methods, machine learning models, and deep learning approaches. The models implemented are:

- **Naïve Forecasting** (Baseline model)
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **Random Forest Regressor**
- **XGBoost**
- **LSTM (Long Short-Term Memory Neural Network)**

## Requirements
Ensure you have the necessary dependencies installed before running the project. You can install them using:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow xgboost missingno
```

## Dataset
The project uses the following datasets:
- `train.csv`: Contains historical sales data.
- `test.csv`: Test data for sales prediction.
- `stores.csv`: Store-related information.
- `oil.csv`: Daily oil prices (important for economic context).
- `holidays_events.csv`: Holidays and events impacting sales.
- `transactions.csv`: Transaction data for stores.

## Running the Project
1. Load and preprocess the datasets.
2. Handle missing values using interpolation and forward fill methods.
3. Perform feature engineering to extract useful date-based features.
4. Train multiple forecasting models.
5. Evaluate model performance using RMSE, MAPE, and R-Squared.
6. Visualize actual vs. predicted sales trends.
7. Analyze feature importance for decision-making.


## Performance Comparison
The models are evaluated using:
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Percentage Error (MAPE)**
- **R-Squared Score**

> **Note:** LSTM and ARIMA models take more time to run, depending on system specifications.

## Business Insights
- **Best Performing Model**: The model with the lowest RMSE and highest R-Squared score is preferred.
- **Impact of External Factors**:
  - Oil prices influence sales trends due to economic conditions.
  - Holiday seasons see fluctuations in sales volume.
  - Promotions and discounts can significantly boost sales.
- **Recommendations**:
  - Use accurate sales forecasting for **inventory planning**.
  - Implement **targeted promotions** during peak sales periods.
  - Monitor economic indicators like oil prices for demand forecasting.

## Conclusion
This project demonstrates the power of various forecasting models in predicting sales trends. Choosing the right model depends on accuracy, computational efficiency, and business requirements. 🚀

