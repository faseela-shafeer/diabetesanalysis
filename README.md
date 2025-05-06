# 🩺 Diabetes Prediction using Machine Learning

This project uses various machine learning models to predict whether a patient is diabetic (or at risk) based on health-related attributes. It simplifies the original multiclass labels into a binary classification: Non-Diabetic vs. Diabetic/At-Risk.

---

## 📊 Dataset

- **Source**: [Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss/)
- **File**: `diabetes.csv`
- **Features**: Demographic, behavioral, and health-related variables.
- **Target Variable**: `Diabetes_012` (converted to binary `DiabetesBinary`)

### Binary Mapping
- `0` → Non-Diabetic
- `1` or `2` → Diabetic or At Risk

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Naive Bayes
- Gradient Boosting

---

## 📈 Performance Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The best model is selected based on **highest accuracy**, with potential for domain-specific adjustments (e.g., using F1 score).

---

## 📦 Requirements

Install the required packages:
pip install pandas scikit-learn matplotlib seaborn 
```bash
pip install pandas scikit-learn matplotlib seaborn xgboost
