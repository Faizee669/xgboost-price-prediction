# 🏡 XGBoost House Price Prediction

This repository contains a machine learning solution to predict house prices using the XGBoost regression model. The project is based on the [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition dataset.

---


---

## 🚀 What This Project Covers

- Exploratory Data Analysis (EDA)
- Handling missing values
- Feature encoding and transformation
- Hyperparameter tuning using RandomizedSearchCV
- Training an XGBoost Regressor
- Evaluation using RMSE and R² metrics
- Generating submission file for Kaggle

---

## 📊 Model Used

We use [XGBoost](https://xgboost.readthedocs.io/en/stable/) — a scalable and accurate gradient boosting machine learning algorithm.

### Tuned Hyperparameters:
- `n_estimators`
- `learning_rate`
- `max_depth`
- `subsample`
- `colsample_bytree`

RandomizedSearchCV was used for efficient hyperparameter tuning.

---

## 📈 Performance

- **Test RMSE**: ~24802.49  
- **Test R²**: 0.9198

These scores indicate a strong fit for predicting house prices.

---

## 📦 Requirements

Install required libraries using pip:

```bash
pip install xgboost scikit-learn pandas matplotlib numpy
