# Walmart Sales Prediction  

This project builds an XGBoost regression model to predict weekly sales for Walmart stores. The dataset is processed by extracting key date-based features such as Year, Month, Week, and Day of the Week. The model is fine-tuned using RandomizedSearchCV to find the best hyperparameters. Performance is evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).  

# How to Use  
1. Install dependencies: `pip install -r requirements.txt`  
2. Train the model: `python train_model.py`  
3. The trained model is saved using `joblib` for future predictions.  

This project helps in understanding sales trends and making data-driven business decisions. 🚀  
