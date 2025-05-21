### Predicting Rainfall Using Random Forest & Logistic Regression built with: 
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Matplotlib** & **Seaborn** for data visualization  
- **Scikit-Learn** for machine learning (Random Forest, Logistic Regression)  
- **StandardScaler** & **OneHotEncoder** for feature preprocessing  
- **GridSearchCV** & **Stratified K-Fold** for hyperparameter tuning  

---

## Rainfall Prediction Classifier  

This project applies **Random Forest and Logistic Regression classifiers** to predict rainfall occurrences based on meteorological attributes such as **humidity, temperature, wind speed, cloud cover, and sunshine levels**. It utilizes feature engineering techniques and hyperparameter tuning to optimize classification accuracy.  

## Key Insights:  
- Humidity at 3 PM is the strongest predictor of rainfall, significantly impacting classification accuracy.  
- Pressure levels contribute to rain predictions, with morning and afternoon pressure values showing influence.  
- Random Forest achieves 85% cross-validation accuracy, outperforming Logistic Regression (83%).  
- Feature scaling and categorical encoding enhance model performance, ensuring better classification stability.  
- Overfitting risks in Random Forest can be mitigated by adjusting `max_depth` and `min_samples_split`.  

---

## Dependencies  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## License  

This project is licensed under the MIT License.
