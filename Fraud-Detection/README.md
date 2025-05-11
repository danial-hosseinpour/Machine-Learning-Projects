### Fraud Detection Model built with: 
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data handling  
- **Scikit-Learn** for machine learning models (**Decision Tree**, **SVM**)  
- **Matplotlib** & **Seaborn** for data visualization  
- **StandardScaler** & **Normalization** for feature scaling  
- **ROC AUC Score** & **Hinge Loss** for model evaluation  

---

# Credit Card Fraud Detection Using Machine Learning

This project applies **Decision Trees and Support Vector Machines (SVM)** to detect fraudulent credit card transactions. The dataset contains **transaction details (Time, Amount, anonymized features V1-V28)** with fraud labels, enabling fraud classification using supervised learning techniques.  

### Key Insights:  
- Fraud cases are extremely rare, making it crucial to balance the dataset during training.  
- Features V17, V14, V12, V10, V16, and V3 show the strongest correlation with fraud based on feature importance analysis.  
- Decision Tree (max depth = 4) achieves 96.6% AUC score, demonstrating effective classification performance.  
- SVM model surpasses Decision Tree, achieving 98.4% AUC score, but takes significantly longer to train.  
- StandardScaler and Normalization enhance accuracy, ensuring better feature representation.  

---

## Visualization Gallery 

- Distribution of Fraud Cases (Pie Chart)
- Feature Correlation with Fraud (Bar Chart)

---

## Dependencies 

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tqdm
```

---
## License 

This project is licensed under the MIT License.

