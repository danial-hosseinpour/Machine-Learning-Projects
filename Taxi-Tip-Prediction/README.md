### Predicting Taxi Tip Amounts with Regression Models built with: 
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Matplotlib** & **Seaborn** for data visualization  
- **Scikit-Learn** for machine learning models (Decision Tree Regressor)  
- **StandardScaler** & **MinMaxScaler** for feature preprocessing  
- **Mean Squared Error (MSE)** & **R² Score** for model evaluation  

---

# Taxi Tip Prediction

This project applies **Decision Tree Regression** to estimate taxi tip amounts based on ride-related attributes such as **trip distance, rate codes, payment type, and pickup/drop-off locations**. The model evaluates key variables affecting tip amounts, determining their predictive strength.  

## Key Insights  
- Fare amount has the highest correlation with tip values, reinforcing tip calculation patterns.  
- Trip distance influences tipping behavior, but shows variability based on external factors.  
- Decision Tree models struggled to generalize, achieving a negative R² score, indicating poor predictive accuracy.  
- Higher max-depth settings improve fit, but risk overfitting when depth exceeds 8–12 levels.  
- Data preprocessing (feature selection, normalization) significantly impacts model performance, requiring optimization.  

---

## Visualization
- Feature Correlation with Tip Amount
- Decision Tree Performance Evaluation
- Distribution of Taxi Tips Across Rides  

---

## Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tqdm
```

---

## License

This project is licensed under the MIT License.
