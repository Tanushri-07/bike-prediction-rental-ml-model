# bike-prediction-rental-ml-model

##  Overview
This project predicts bike rental demand using time-series and weather data. The goal is to understand patterns in the data and build a model that can accurately predict demand.

---

##  Approach
- Treated the problem as a time-series problem
- Performed exploratory data analysis (EDA)
- Created time-based features and lag features
- Used Random Forest for prediction
- Applied time-based train-test split


##  Features Used
- Time Features: hour, day_of_week, month, is_weekend  
- Weather Features: temperature, humidity, windspeed  
- Lag Features: lag_1 (previous hour), lag_24 (previous day same hour)


##  Model
- Random Forest Regressor
- Handles non-linear relationships
- Works well with structured data


##  Evaluation
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- Compared performance with a baseline model


##  Key Insights
- Demand shows strong hourly patterns
- Peak usage during morning and evening hours
- Lag features significantly improve prediction accuracy


##  Future Improvements
- Hyperparameter tuning
- Try advanced models like XGBoost
- Include additional features like holidays


##  Files
- `bike_prediction.ipynb` → Main notebook
- `requirements.txt` → Dependencies


## 👨‍💻 Author
- First-year AI/ML student
