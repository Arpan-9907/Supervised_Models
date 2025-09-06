# Vehicle Price Prediction Project

This project focuses on predicting the market price of vehicles using a comprehensive dataset of car features. This is a regression problem aimed at creating a model that can estimate prices accurately.

## 📋 Dataset

The dataset used is `Vehicle_price_Data.csv`. It includes various features like the vehicle's make, model, year, mileage, engine type, and more.

## 🛠️ Process

1.  **Data Cleaning:** Preprocessed the dataset by handling missing values and encoding categorical features.
2.  **Model Training:** Utilized the powerful **XGBoost Regressor**, a gradient-boosting algorithm known for its high performance.
3.  **Hyperparameter Tuning:** Optimized the model using `GridSearchCV` to find the best parameters and improve prediction accuracy.
4.  **Evaluation:** Measured the model's performance with regression metrics like R-squared (R²), Mean Absolute Error (MAE), and Mean Squared Error (MSE).

## 🚀 How to Run

1.  Ensure you have Python and Jupyter Notebook installed.
2.  Install the required libraries:
    ```bash
    pip install pandas scikit-learn xgboost seaborn matplotlib
    ```
3.  Open and run the `VehiclePricePredictionusingXGBoost.ipynb` notebook.
