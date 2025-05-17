# 🍷 Wine Quality Prediction using Random Forest Classifier

This project predicts the quality of wine based on physicochemical features using a **Random Forest Classifier**. The model classifies wine into quality categories and helps understand how each feature affects the overall quality.

---

## 📁 Dataset

- **Link**: [Wine Quality Dataset] 
- **Data**: Contains physicochemical test results of red or white wine samples with a quality score (typically ranging from 3 to 8).

---

## 📌 Features Used

- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- **Target**: `quality` (integer score)

---

## 🎯 Objective

To build a **classification model** that predicts wine quality classes (e.g., 3 to 8) using a Random Forest algorithm.

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values and data distribution
- Visualized feature correlations with a **heatmap**
- Observed that **alcohol** and **sulphates** had strong correlation with wine quality

---

## ⚙️ Model Used

- **Random Forest Classifier**
  - An ensemble of decision trees
  - Handles non-linear relationships well
  - Reduces overfitting compared to individual decision trees

---

## 🧪 Model Evaluation

- Train-Test Split
- Cross-validation (e.g., 5-Fold)
- Metrics used:
  - Accuracy
    - Classification Report (Precision, Recall, F1-score)

---

## 📈 Results

- **Train Accuracy**: 100%
- **Test Accuracy**: ~91%
- **Cross-validation Accuracy**: ~86%
- No signs of overfitting based on validation metrics





