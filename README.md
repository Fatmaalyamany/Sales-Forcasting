# Rossmann Store Sales Forecasting

Time series analysis and sales forecasting for Rossmann stores using Facebook Prophet.

## Overview

This notebook provides complete sales forecasting analysis including data exploration, preprocessing, and predictive modeling with Prophet.

## Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn prophet
```

## Datasets

- `train.csv` - Historical sales data (Store, Date, Sales, Customers, etc.)
- `store.csv` - Store information (StoreType, Competition, Promotions, etc.)
- Data Source: https://www.kaggle.com/c/rossmann-store-sales/data
  
## Features

- **Data Preprocessing**: Missing value handling, feature engineering, data cleaning
- **EDA**: Sales patterns, temporal trends, promotion impact, store performance
- **Forecasting**: Prophet models with seasonality, holidays, and validation
- **Metrics**: MAE, RMSE, MAPE evaluation

## Usage

1. Place `train.csv` and `store.csv` in the notebook directory
2. Run all cells sequentially
3. View generated plots and forecast results

## Key Outputs

- Distribution and correlation analysis
- Temporal sales patterns
- Store performance rankings
- 60-day sales forecasts with confidence intervals
- Model validation metrics

## Customization

```python
# Adjust forecast period
forecast_periods = 60

# Select stores to analyze
sample_stores = [1, 10, 25, 50, 100]
```

Built for retail sales forecasting with automated analysis and visualization.
