# 🛒 Product Sales Forecasting using Tree-Based Regression Models
This project presents a robust and practical machine learning pipeline for forecasting product sales based on structured retail data. It leverages comprehensive data analysis, feature engineering, and tree-based regression models to accurately predict the number of products sold.
## 🔍 Key Highlights:
- **Exploratory Data Analysis (EDA):** Identified missing values, feature distributions, and relevance of categorical variables like `store_id` and `sku_id`.
- **Custom ML Pipelines:** Built using `sklearn.pipeline` for modular preprocessing and modeling, including categorical encodings and optional transformations.
- **Tree-Based Models:** Trained and compared performance of `Random Forest` and `CatBoost Regressor`, with a simple baseline for reference.
- **Metrics Evaluation:** Performance was assessed using MAE, MSE, RMSE, and R². CatBoost outperformed others, achieving the lowest error rates.
- **Visualization:** Actual vs. Predicted plots and bar charts for comparative metric evaluation.
- **Production-Ready Structure:** Reusable functions for evaluation and a clean, maintainable notebook layout.
