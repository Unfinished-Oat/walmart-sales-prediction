# Walmart Sales Prediction  

This project develops an XGBoost regression model to predict weekly sales for Walmart stores. It extracts key date-based features (Year, Month, Week, Day of the Week) and fine-tunes the model using RandomizedSearchCV to optimize hyperparameters. Performance is measured using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

# How to Use  
1. Install dependencies: pip install -r requirements.txt
2. Train the model: python train_model.py
3. The trained model is saved as xgboost_sales_model.pkl using joblib for future predictions.

This project provides insights into sales trends and aids in data-driven business decisions.
