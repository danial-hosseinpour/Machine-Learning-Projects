### Predicting Customer Categories with K-Nearest Neighbors (KNN) built with:  
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Matplotlib** & **Seaborn** for visualization  
- **Scikit-Learn** for machine learning (**KNN**, **Stratified K-Fold**, **GridSearchCV**, **XGBoost**)  
- **StandardScaler** & **PCA** for feature preprocessing  

---

## Tele-Customer Classification Using Machine Learning 

This project applies **K-Nearest Neighbors (KNN) Classification** to categorize telecom customers based on attributes like **tenure, income, employment status, and household residence**. Through **hyperparameter tuning and dimensionality reduction**, it improves classification performance while exploring correlations between customer categories.  

## Key Insights:  
- Education level (`ed`) has the highest correlation with customer category (`custcat`), followed by tenure and income.  
- KNN accuracy improves with `k=38`, achieving 41% test accuracy, showing optimal neighborhood selection impacts performance.  
- Dimensionality reduction via PCA enhances generalization, reducing feature complexity while maintaining predictive power.  
- XGBoost with hyperparameter tuning outperforms KNN, achieving 42.5% accuracy using stratified sampling.  
- Class imbalances affect results, requiring weighted training approaches for balanced predictions.  

---

## Visualization

- Correlation Heatmap of Customer Features 
- KNN Accuracy vs. Number of Neighbors (k)
- Confusion Matrix for Classification Pipeline 


---

## Dependencies 

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

---

## License  

This project is licensed under the MIT License.


