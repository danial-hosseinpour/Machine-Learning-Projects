# Telecommunication Customer Classification Project

This project applies various machine learning techniques—including K-Nearest Neighbors (KNN) and XGBoost—to classify customers in the **TeleCust1000t** dataset. It explores preprocessing strategies, model tuning, and dimensionality reduction to understand what impacts classification accuracy.

## 🧠 Objective

To predict the **`custcat`** label (customer category) using various customer attributes like income, age, education, employment, and region. The classification performance is currently limited, and the project will be iteratively improved.

---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Scikit-learn (KNN, PCA, Pipelines, GridSearchCV)
- Seaborn, Matplotlib (for data visualization)
- XGBoost (Gradient boosting model)
- KaggleHub (for dataset loading)

---

## 🧪 Methods

- **Data Preprocessing:**
  - Standardization using `StandardScaler`
  - Feature selection experiments with various subsets
- **Modeling Techniques:**
  - KNN Classification with hyperparameter tuning
  - XGBoost with class balancing and cross-validation
- **Evaluation:**
  - Accuracy
  - Confusion matrix visualization
- **Dimensionality Reduction:**
  - PCA used to reduce features for better KNN performance

---

## 📉 Results

- Best accuracy achieved with KNN: *Low (0.435)*
- Accuracy varies based on feature subset, number of neighbors, and PCA components
- XGBoost was tested with stratified cross-validation and sample weighting, but also produced relatively low accuracy

---

## 📌 TODO / Future Work

- Perform deeper **feature engineering** and encoding
- Try **SMOTE** or **class balancing** for imbalanced classes
- Evaluate with **other classifiers** (SVM, Random Forest, etc.)
- Visualize **decision boundaries** of KNN
- Tune **XGBoost parameters** more extensively
- Add **metrics beyond accuracy** (e.g., F1-score, AUC)

---

## 📂 Dataset Info

- Dataset: [`TeleCust1000t`](https://www.kaggle.com/datasets/damlaerek0/telecust1000t) (Kaggle)
- Columns include: `tenure`, `age`, `income`, `marital`, `employ`, `ed`, `gender`, etc.

---

## 💡 Final Notes

This is a work in progress. The current results are not satisfactory in terms of accuracy, but this project serves as a valuable baseline for improving classification pipelines and understanding the customer segmentation problem better.

