# Cardiovascular-Risk-Prediction
# 🩺 Cardiovascular Risk Prediction Pipeline

An end-to-end machine learning classification pipeline designed to predict cardiovascular disease risk using clinical and demographic patient data. This project incorporates data preprocessing, severe class imbalance handling with **SMOTE**, and robust model evaluation using **Confusion Matrices** and **ROC-AUC Scores**.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Imbalanced-learn (SMOTE), Pandas, NumPy, Seaborn, Matplotlib

---

## 🚀 Quick Start & Exploration
You can explore the complete interactive Jupyter notebook and run the pipeline directly in your browser using Google Colab:
👉 **[Open and Run in Google Colab](https://colab.research.google.com/drive/YOUR_ACTUAL_LINK)**

---

## 📊 Pipeline Workflow
1. **Data Preprocessing & Scaling:** Cleaned missing target values and standardized features using `StandardScaler`.
2. **Handling Class Imbalance:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the training dataset and prevent model bias.
3. **Model Training:** Trained a robust **Random Forest Classifier** to accurately classify patient risk levels.
4. **Evaluation:** Evaluated performance metrics using Classification Reports, Confusion Matrices, and ROC-AUC Curves.
---

## 📈 Evaluation Metrics & Results
Our trained **Random Forest Classifier** achieved exceptional diagnostic performance on the clinical dataset:
* **ROC-AUC Score:** **0.94** (indicating high reliability in distinguishing between risk levels)
* **Handling Imbalance:** Successfully mitigated class bias using `SMOTE` during training.
### Model Visualizations

**Confusion Matrix:**
![Confusion Matrix](Confusion%20matrix.png)

**ROC-AUC Curve:**
![ROC Curve](ROC%20curve.png)
