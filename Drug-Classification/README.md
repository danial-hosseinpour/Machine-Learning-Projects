# Drug Prescription Classification Using Decision Trees

This project explores a simple classification task using the **Drug200** dataset. A **Decision Tree Classifier** is trained to predict which drug a patient should be prescribed based on several health-related attributes.

---

## 📌 Project Objective

To classify which drug (`drugA`, `drugB`, `drugC`, `drugX`, or `drugY`) a patient will be prescribed based on:

- Age  
- Sex  
- Blood Pressure (BP)  
- Cholesterol  
- Sodium to Potassium ratio (`Na_to_K`)  

---

## 📂 Dataset

- Source: [`Drug200`](https://www.kaggle.com/datasets/jeevanrh/drug200csv) from Kaggle  
- Records: 200  
- Features:
  - Categorical: `Sex`, `BP`, `Cholesterol`
  - Numerical: `Age`, `Na_to_K`
  - Target: `Drug` (Drug type to be prescribed)

---

## 🛠️ Libraries & Tools

- **Pandas / NumPy** for data handling  
- **Seaborn / Matplotlib** for visualization  
- **Scikit-learn** for:
  - Label Encoding
  - Train-Test Split
  - Decision Tree Classifier
  - Accuracy Metric
  - Tree Visualization (`plot_tree`)  
- **KaggleHub** for dataset access

---

## 🧪 Methodology

1. **Data Preprocessing**
   - Categorical features encoded using `LabelEncoder`
   - Target classes (`Drug`) mapped to numeric values for correlation analysis

2. **Model Training**
   - Used `DecisionTreeClassifier` from `sklearn`
   - `entropy` criterion and different `max_depth` values tested
   - Trained on 70% of the data, tested on 30%

3. **Evaluation**
   - Performance measured using `accuracy_score`
   - Decision tree visualized using `plot_tree`

---

## 📊 Results

- Decision Tree with `max_depth=4`: Good balance between complexity and interpretability  
- Accuracy varies depending on tree depth (sample results: ~0.90+)
- Visualized tree reveals clear rules for drug classification

---

## 📈 Visualization Samples

- Countplot of drug distribution  
- Decision tree diagram to illustrate model logic  
- Correlation heatmap (optional based on extended version)

---

## 🔍 Future Improvements

- Try other models like **Random Forest**, **XGBoost**, or **Logistic Regression**
- Apply **cross-validation** to improve generalization
- Perform **feature importance** analysis
- Deploy as an **interactive app** (e.g., with Streamlit)

---

## 💡 Final Note

This is a simple but effective project to demonstrate **decision tree learning**, especially in the healthcare domain. It showcases how easy-to-understand models can still achieve good results with clean data and thoughtful preprocessing.


