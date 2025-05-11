### Breast Cancer Prediction Built With:

- **Scikit-learn** for machine learning models (**SVC**, **KNeighborsClassifier**) and evaluation (**accuracy_score**, **classification_report**, **confusion_matrix**)
- **Seaborn** & **Matplotlib** for insightful and clear data visualizations
-  **Pandas** & **NumPy** for data preprocessing and manipulation
-  **StandardScaler** for feature normalization
---

# Breast Cancer Classification
## Project Overview

This project aims to classify breast tumors as **malignant** or **benign** using the **Breast Cancer Wisconsin Diagnostic dataset**. By exploring the relationships among clinical features and applying multiple classification algorithms, the project seeks to identify the most accurate and reliable model for medical decision support.

---

## Key Features

* Cleaned and prepared diagnostic data containing **30 numeric features** extracted from digitized images of breast masses.
* Label encoding of diagnosis target (`M` = 1, `B` = 0)
* Multiple classifiers implemented and evaluated:

  * K-Nearest Neighbors
  * Support Vector Machine (RBF kernel)
* ROC-AUC analysis for deep model performance understanding
* Comparative model evaluation with metrics: **accuracy, precision, recall, F1-score**

---

## Workflow Summary

1. **Data Import & Cleaning**

   * Loaded dataset, dropped irrelevant columns (ID), checked for nulls.

2. **EDA (Exploratory Data Analysis)**

   * Count plots of diagnosis types (Benign/Malignant)
   * Identified highly correlated features: `radius_mean`, `perimeter_mean`, `area_mean`

3. **Preprocessing**

   * Label encoding (M = 1, B = 0)
   * Feature scaling using `StandardScaler`
   * Data split into 80% training / 20% test sets

4. **Modeling & Evaluation**

   * Trained five classifiers
   * Evaluated using accuracy, confusion matrix, and classification report
   * Visual comparison of confusion matrices
---

## Visualizations

* Diagnosis class distribution
* Confusion matrices for each model

---

## Conclusion – Best Performing Model

* **SVM** achieved the best overall performance:

  * **Accuracy**: 97.1%
  * **Precision**: 97%
  * **Recall**: 97%
  * **F1-Score**: 97%
* It offered the most balanced and accurate results, ideal for medical use cases where minimizing false negatives is critical.

