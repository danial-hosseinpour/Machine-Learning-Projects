### Predicting California Housing Prices with Advanced Regression Models built with:  
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Matplotlib** & **Seaborn** for data visualization  
- **Scikit-Learn** for modeling (Random Forest, XGBoost)  
- **Mean Squared Error (MSE)**, **Mean Absolute Error (MAE)**, **R² Score** for evaluation metrics  

---

# California Housing Price Prediction

This project applies **Random Forest and XGBoost regression models** to predict median house values in California based on census block attributes such as **income levels, population, and household occupancy**. It evaluates model performance and compares results using multiple regression techniques.  

## Key Insights: 
- Median income has the highest correlation with house prices, making it the most important feature for prediction.  
- Random Forest achieves an R² score of 80.5%, whereas XGBoost improves performance to 83.0%, demonstrating higher accuracy.  
- XGBoost trains significantly faster, completing in 0.33 seconds compared to Random Forest’s 20.93 seconds.  
- Feature importance analysis ranks median income, latitude, and average occupancy as top contributors to housing price predictions.  
- Residual analysis reveals prediction errors, helping identify potential model biases.  

---

## Visualization  

- Distribution of California Median House Prices
- Random Forest vs XGBoost Predictions
- Residual Errors Analysis for Both Models 
- Feature Importance in Predicting House Prices

---

## Dependencies 

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

---

## License 

This project is licensed under the MIT License.

