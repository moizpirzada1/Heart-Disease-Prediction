# Heart-Disease-Prediction
# 🧠 Task 3 - Heart Disease Prediction using Logistic Regression

This repository contains the third task of an AI/ML internship project. The goal is to build a logistic regression model that predicts the presence of heart disease using clinical data from patients. The entire process includes data cleaning, exploratory data analysis (EDA), feature scaling, model training, and performance evaluation.

---

## ✅ Task Objective

- Load and clean a real-world heart disease dataset.
- Visualize correlations and data distributions.
- Train a **Logistic Regression** model.
- Evaluate the model using classification metrics, ROC curve, and confusion matrix.
- Interpret model coefficients to understand feature importance.

---

## 📊 Dataset Used

- **File**: `heart_cleveland_upload.csv`
- **Source**: Derived from the [UCI Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Records**: 303 patients
- **Features**:
  - `age`: Age in years
  - `sex`: Gender (1 = male, 0 = female)
  - `cp`: Chest pain type (0–3)
  - `trestbps`: Resting blood pressure
  - `chol`: Serum cholesterol
  - `fbs`: Fasting blood sugar > 120 mg/dl
  - `restecg`: Resting electrocardiographic results
  - `thalach`: Maximum heart rate achieved
  - `exang`: Exercise induced angina
  - `oldpeak`: ST depression induced by exercise
  - `slope`, `ca`, `thal`: Additional clinical variables
  - `num` or `target`: Presence of heart disease (converted to binary: 1 = disease, 0 = no disease)

---

## 🤖 Model Applied

- **Logistic Regression** from scikit-learn was used as the classification algorithm.
- Features were standardized using `StandardScaler`.
- Evaluation included:
  - **Accuracy Score**
  - **Classification Report** (Precision, Recall, F1-score)
  - **Confusion Matrix**
  - **ROC Curve and AUC Score**
  - **Feature Importance** via logistic regression coefficients

---

## 📈 Key Results and Findings

- **Accuracy**: Achieved a strong classification accuracy on the test set.
- **ROC-AUC Score**: Showed good model performance with strong separation between classes.
- **Feature Importance**: Variables like `cp`, `thalach`, `oldpeak`, and `ca` had significant influence on predictions.
- The logistic regression model is interpretable, efficient, and effective for binary classification on structured clinical data.

---

## 📁 File Structure

