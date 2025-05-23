# 🛒 Product Sales Forecasting using Tree-Based Regression Models
This project presents a practical machine learning pipeline for forecasting product sales based on structured retail data. It leverages comprehensive data analysis, feature engineering, and tree-based regression models to accurately predict the number of products sold.


<img src="https://github.com/JavierKaiser9/Product_sales_forecasting/blob/main/PF.jpg" width="400" alt="data_analysis" title="data_analysis" />



## 📊 Project Workflow

1. **Exploratory Data Analysis (EDA)**
   - Identified distributions, outliers, and feature relationships.
   - Analyzed correlation between features and the target variable (`units_sold`).

2. **Data Cleaning and Preparation**
   - Handled missing values and date formatting.
   - Transformed categorical variables as necessary.

3. **Feature Engineering**
   - Separated features from target.
   - Implemented transformations and scalers where needed.
   - Built a preprocessing pipeline using `ColumnTransformer`.

4. **Modeling**
   - Developed models using:
     - **Random Forest Regressor**
     - **CatBoost Regressor**
   - Implemented train/test splits and evaluated predictions.

5. **Hyperparameter Tuning**
   - Applied **Grid Search Cross-Validation (GridSearchCV)** to find optimal parameters for both Random Forest and CatBoost.
   - Tuned parameters such as:
     - `n_estimators` for Random Forest.
     - `depth` and `iterations` for CatBoost.
   - Chose best models based on lowest RMSE and highest R².

6. **Evaluation Metrics**
   - **MAE**: Mean Absolute Error
   - **MSE**: Mean Squared Error
   - **RMSE**: Root Mean Squared Error
   - **R² Score**: Coefficient of Determination

---

## 📁 How to Run

1. Clone the repository.
2. Run `Product_Forecasting.ipynb` using Jupyter.
4. Modify paths and parameters if necessary.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- CatBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📚 Dataset Source

The dataset used in this project was obtained from:

- [Demand Forecasting Dataset by Aswath Rao](https://www.kaggle.com/datasets/aswathrao/demand-forecasting)

Note: This dataset was publicly available at the time of use. Please refer to the dataset page for any updates or terms of use.
