### Predicting Customer Churn with Logistic Regression built with:**  
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Matplotlib** & **Seaborn** for data visualization  
- **Scikit-Learn** for machine learning (**Logistic Regression**, **StandardScaler**)  
- **Train-Test Split** & **Log Loss Evaluation** for model validation  

---

# Telecom Customer Churn Prediction

This project applies **Logistic Regression** to predict customer churn in a telecom dataset. The model evaluates key customer attributes such as **tenure, income, age, employment status, and equipment type** to determine likelihood of churn.  

### **Key Insights:**  
- Tenure has the highest negative correlation with churn, meaning long-term customers are less likely to leave.  
- Equipment type strongly influences churn, with certain devices associated with higher churn rates.  
- Feature scaling improves model efficiency, ensuring consistent weight distribution.  
- Logistic Regression achieves a log loss score of 0.530, indicating moderate predictive accuracy.  
- Refining features significantly impacts results, where removing unnecessary columns improves performance.  

 
---

## Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## License  

This project is licensed under the MIT License.

