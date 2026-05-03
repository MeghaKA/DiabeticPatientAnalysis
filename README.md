# 🩺 Diabetic Patient Analysis & Prediction using Machine Learning

## 📌 Project Overview
This project applies machine learning techniques to predict the likelihood of diabetes based on patient health indicators. The objective is to support early detection and assist in clinical decision-making through data-driven insights.

The model not only focuses on prediction accuracy but also emphasizes **interpretability using SHAP explainability techniques**, making the system more transparent and aligned with healthcare applications.

---

## 🎯 Objective
To build a machine learning model that:
- Predicts diabetes risk using patient medical attributes
- Identifies key health factors influencing predictions
- Provides explainable AI outputs for clinical interpretation

---

## 📊 Dataset Features
The dataset includes key health indicators:

- Pregnancies  
- Glucose Level  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI (Body Mass Index)  
- Diabetes Pedigree Function  
- Age  

---

## ⚙️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- SHAP (Explainable AI)  
- Jupyter Notebook  

---

## 🔍 Workflow
- Data loading and preprocessing  
- Feature selection and scaling  
- Model training (Logistic Regression, SVM, Decision Tree, AdaBoost, CatBoost)  
- Model evaluation (Accuracy, Precision, Recall, F1-score)  
- Explainability using SHAP  

---

## 📈 Model Performance
Multiple machine learning models were evaluated, and Decision Tree showed competitive performance among baseline models.

---

## 🧠 SHAP Explainability Insights

- SHAP analysis revealed that **High Blood Pressure, High Cholesterol, and BMI** are the most influential predictors of diabetes risk.
- Higher values of these features consistently increased model prediction output.
- These findings align with established medical knowledge, confirming model interpretability.
- The system demonstrates both predictive accuracy and clinical transparency.

### 🔬 Patient-Level Insight
SHAP-based local explanations show how individual features contribute to a specific patient's predicted risk, improving trust in model decisions.

---

## 📁 Repository Structure
- `notebook.ipynb` → Full analysis workflow  
- `train.csv / test.csv` → Dataset files  
- `shap_summary.png` → Global feature importance visualization  
- `shap_bar.png` → Feature ranking plot  

---

## 👩‍💻 Author
**Megha K A**  
Data Analyst | Machine Learning Enthusiast  
Python | SQL | Cloud Analytics | AI in Healthcare
