# 🩺 Explainable Diabetes Prediction using Machine Learning (XAI)

## 🎯 Overview  
This project focuses on predicting diabetes risk using machine learning models and improving transparency using Explainable AI (XAI).

In healthcare, predictions alone are not sufficient — understanding why a prediction is made is critical for trust and decision-making.  
This project applies SHAP (SHapley Additive Explanations) to interpret model predictions and identify key risk factors.

---

## ⚙️ Tech Stack  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- SHAP (Explainable AI)  
- Matplotlib  

---

## 🚀 Project Workflow  

1. Data preprocessing and cleaning  
2. Feature selection and preparation  
3. Model training (Decision Tree / Random Forest)  
4. Model evaluation (Accuracy, Precision, Recall)  
5. Explainability using SHAP  

---

## 📊 Model Performance  
The model demonstrates strong predictive capability for diabetes classification using supervised learning techniques.

---

## 🔍 Explainable AI (SHAP Analysis)

To improve interpretability, SHAP is used to analyze feature importance and understand how each variable influences predictions.

### 📌 SHAP Summary Plot  

SHAP Summary

---

## 🧠 Key Insights from SHAP  

The SHAP analysis reveals the most influential features affecting diabetes prediction:

### 🔴 High Impact Features  
- General Health (GenHlth) → strongest overall predictor  
- High Blood Pressure (HighBP) → significantly increases risk  
- Age → higher age contributes to higher predicted risk  
- BMI → strong positive correlation with diabetes  
- High Cholesterol (HighChol) → increases risk  

### 🟡 Moderate Impact Features  
- Income → lower income associated with higher risk  
- Physical Health (PhysHlth) → poor physical health increases risk  
- Education → lower education levels show higher risk trends  
- Physical Activity (PhysActivity) → reduces risk  

### 🔵 Lower Impact Features  
- Lifestyle and demographic factors such as:
  - Smoking  
  - Alcohol consumption  
  - Fruit & vegetable intake  
  - Stroke history  

These features contribute less compared to core clinical indicators.

---

## 🧠 Interpretation  

- Features on the right side (positive SHAP values) increase diabetes risk  
- Features on the left side (negative SHAP values) decrease risk  
- Red color indicates higher feature values, blue indicates lower values  

This helps understand both:
✔ Feature importance  
✔ Direction of impact  

---

## 🧠 Why This Matters  

In real-world healthcare applications:

- Black-box models are difficult to trust  
- Clinicians require interpretable insights  

This project demonstrates how machine learning can be:

✔ Accurate  
✔ Transparent  
✔ Clinically interpretable  

---

## 🔮 Future Work  

- Extend analysis to Chronic Kidney Disease (CKD)  
- Compare SHAP with LIME or CECS and counterfactual explanations  
- Develop clinician-aligned explainability metrics (research direction)  

---

## 👩‍💻 Author  
Megha K A  
Data Analyst | Machine Learning | Explainable AI
