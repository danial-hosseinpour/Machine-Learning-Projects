### Predicting Passenger Survival on the Titanic built with:  
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Matplotlib** & **Seaborn** for visualization  
- **Scikit-Learn** for machine learning (**Random Forest**, **Logistic Regression**)  
- **StandardScaler** & **OneHotEncoder** for feature preprocessing  
- **GridSearchCV** & **Stratified K-Fold** for hyperparameter tuning  

---

# Titanic Survival Prediction

This project applies **Random Forest and Logistic Regression classifiers** to predict passenger survival based on attributes such as **age, gender, ticket class, family connections, and fare amount**. It incorporates **hyperparameter tuning and feature importance analysis** to optimize classification performance.  

## Key Insights: 
- Fare amount and passenger class are strong predictors of survival, with first-class passengers having a higher survival rate.  
- Gender is a critical survival factor, as female passengers had significantly higher survival probabilities than males.  
- Random Forest achieves 83% test accuracy, outperforming Logistic Regression’s 82.68%.  
- Feature preprocessing (scaling and categorical encoding) enhances classification stability, reducing bias.  
- Handling missing data effectively improves model performance, particularly for `age` and `embarked` attributes.  

---

## Visualization 
- Confusion Matrix for Random Forest Model
- Feature Importance in Titanic Survival Prediction**  



---

## Dependencies 

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Licens 

This project is licensed under the MIT License.
