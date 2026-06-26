# Hunar-intern-task-2
# House Price Prediction Pipeline (Task-2)

This repository contains a robust, end-to-end Machine Learning pipeline designed to predict housing prices using a **Random Forest Regressor**. It includes comprehensive data preprocessing, automatic handling of categorical variables via one-hot encoding, model training, and performance evaluation.

## 🚀 Features
* **Automated Data Preprocessing**: Automatically drops non-predictive identifier columns (like `Id`) if present.
* **Categorical Encoding**: Dynamically detects and applies One-Hot Encoding to categorical columns (such as `city`).
* **Robust Modeling**: Employs an ensemble-based `Random Forest Regressor` to capture complex, non-linear relationships in housing data better than standard linear models.
* **Performance Metrics**: Outputs comprehensive evaluation diagnostics including MAE, RMSE, and $R^2$ Score.
* **Feature Importance**: Evaluates and displays which structural or geographical features impact housing prices the most.

---

## 📁 Project Structure
```text
├── housing_data.csvtext     # Your housing dataset (ensure this matches your file name)
├── house_price_pred.py     # Main Python execution script
└── README.md               # Project documentation
