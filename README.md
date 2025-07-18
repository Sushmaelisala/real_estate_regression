# real_estate_regression

# 🏠 Real Estate Price Prediction

This project focuses on predicting real estate property prices using various regression models. It involves preprocessing real estate data, analyzing features, and selecting the best-performing model based on evaluation metrics.



## 🧾 Dataset

The dataset includes common features found in real estate listings, such as:

- `Area`
- `Bedrooms`
- `Bathrooms`
- `Stories`
- `Mainroad`, `Guestroom`, `Basement`, `HotwaterHeating`, etc.
- `Parking`, `Airconditioning`, `Prefarea`
- **Target Variable**: `Price`





## 🎯 Objective

To build a regression model that accurately predicts the price of a house based on its characteristics and amenities.


## 🛠️ Technologies Used

- Python 3.x
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- xgboost
- Jupyter Notebook

## 📊 Workflow

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables (LabelEncoding / OneHotEncoding)
   - Feature selection

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots
   - Correlation heatmaps
   - Outlier detection

3. **Model Building**
   - Train/test split
   - Regression models used:
     - Linear Regression
     - Random Forest Regressor
     - Support Vector Regressor (SVR)
     - XGBoost Regressor

4. **Model Evaluation**
   - R² Score
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - Visualizations of predicted vs actual values

📌 Future Enhancements:

- Hyperparameter tuning with GridSearchCV

- Feature importance ranking

-Deploying as a web app using Streamlit or Flask.

✅ Output:

- Performance metrics for each regression model

- Scatter plot of actual vs predicted prices

- Best model identified based on R² and RMSE

