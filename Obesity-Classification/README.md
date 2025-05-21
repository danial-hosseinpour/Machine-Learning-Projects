### Predicting Obesity Risk Levels with Multi-Class Classification built with:
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Matplotlib** & **Seaborn** for data visualization  
- **Scikit-Learn** for machine learning (**Logistic Regression**, **SVM**, **One-vs-One**, **One-vs-Rest**)  
- **StandardScaler** & **OneHotEncoder** for feature engineering  

---

# Obesity Classification

This project applies **Logistic Regression, Support Vector Machines (SVM), and multi-class classification strategies** to predict obesity risk levels based on various lifestyle and health-related features. It utilizes **One-vs-One (OvO) and One-vs-Rest (OvR) classifiers**, alongside feature importance analysis, to refine predictive modeling.  

## Key Insights 
- Body weight and eating habits strongly influence obesity classification, as seen in feature importance rankings.  
- Logistic Regression with One-vs-One strategy achieves 92.2% accuracy, outperforming One-vs-Rest (76.1%).  
- Standardized numerical features improve classification stability, reducing bias from varying scales.  
- SVM with optimized hyperparameters reaches 94.6% accuracy, demonstrating strong predictive power.  
- Feature selection impacts results, where `Sodium-to-Potassium Ratio (Na_to_K)`, `Weight`, and `Family History with Overweight` ranked as top predictors.  

---

## Visualization

- Feature Importance in Obesity Prediction  

- Distribution of Obesity Levels Among Individuals

- Decision Boundary for SVM Classifier 

---

## Dependencies 

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## License

This project is licensed under the MIT License.

