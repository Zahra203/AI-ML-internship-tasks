# Task 6: House Price Prediction

##  Objective
Predict house prices based on features such as square footage, number of bedrooms, and location (zipcode).

---

##  Dataset
- **Name**: King County House Sales Dataset
- **Source**: Kaggle
- **Rows**: ~21,000
- **Target**: `price`

###  Features Used

| Feature      | Description                          |
|--------------|--------------------------------------|
| `sqft_living`| Living area in square feet           |
| `bedrooms`   | Number of bedrooms                   |
| `bathrooms`  | Number of bathrooms                  |
| `floors`     | Number of floors                     |
| `zipcode`    | Location (used as a categorical var) |

---

##  Models Used
- Linear Regression
- Gradient Boosting Regressor

---
##  Final Insights – Task 6: House Price Prediction

- The dataset contains rich features such as square footage, bedrooms, and location (zipcode).
- After preprocessing and encoding, two models were tested:
  - Linear Regression
  - Gradient Boosting Regressor
- Gradient Boosting performed better with **lower MAE and RMSE** values.
- Zipcode significantly affects pricing — proving location is key in real estate.
- The model is capable of predicting house prices with reasonable accuracy.

---

##  Libraries Used

| Library           | Purpose                                      |
|-------------------|----------------------------------------------|
| `pandas`          | Data handling                                |
| `numpy`           | Numerical calculations                       |
| `matplotlib`      | Plotting graphs                              |
| `seaborn`         | Advanced visualizations                      |
| `sklearn.linear_model` | Linear Regression                     |
| `sklearn.ensemble` | Gradient Boosting                          |
| `sklearn.metrics` | MAE, RMSE evaluation                        |
| `sklearn.preprocessing` | Feature scaling (StandardScaler)     |

---

##  Files
- `house_price_prediction.ipynb`: Full notebook with modeling
-  dataset  
- `README.md`: Task overview and summary
