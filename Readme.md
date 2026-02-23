# 🩺 Breast Cancer Classification using Logistic Regression

An end-to-end **machine learning classification project** to predict whether a tumor is **malignant or benign** using Logistic Regression. This project demonstrates a **complete ML pipeline** including data preprocessing, feature scaling, model training, advanced evaluation metrics, ROC-AUC analysis, threshold tuning, and feature importance interpretation.

---

## 📌 Project Overview

Early detection of breast cancer significantly improves treatment outcomes and survival rates. This project aims to build a **robust and reliable binary classification system** using Logistic Regression to assist in early diagnosis by predicting tumor malignancy based on diagnostic features.

This project was developed as part of **Task 4 of an AI/ML Internship**.

---

## 🎯 Objectives

- Implement Logistic Regression for binary classification  
- Perform feature scaling using StandardScaler  
- Evaluate model using confusion matrix, precision, recall, and accuracy  
- Perform **ROC curve and AUC score analysis**  
- Apply **threshold tuning** to optimize recall  
- Understand and visualize the **sigmoid function**  
- Perform **feature importance analysis**  

---

## 🧰 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Dataset Information

**Dataset Name:** Breast Cancer Wisconsin Dataset  

**Number of Samples:** 569  
**Number of Features:** 30  

**Target Variable:**  
- `0` → Malignant  
- `1` → Benign  

---

## ⚙️ Project Workflow

1. Data Loading & Inspection  
2. Feature Scaling using StandardScaler  
3. Train-Test Split  
4. Logistic Regression Model Training  
5. Model Evaluation  
6. Confusion Matrix & Classification Report  
7. ROC Curve & AUC Score Analysis  
8. Threshold Tuning  
9. Sigmoid Function Visualization  
10. Feature Importance Analysis  

---

## 📊 Model Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  
- ROC-AUC Score  

---

## 📈 Visualizations

- Confusion Matrix Heatmap  
- ROC Curve  
- Sigmoid Function Plot  
- Feature Importance Plot  

---

## 🔍 Key Insights

- Logistic Regression achieved **high classification accuracy and excellent recall**.
- Threshold tuning significantly improved recall, reducing **false negatives**, which is critical for medical diagnosis.
- ROC-AUC analysis demonstrated **strong discriminative capability** of the model.
- Feature importance analysis highlighted key diagnostic parameters influencing tumor classification.

---

## 📁 Repository Structure

```
Breast-cancer-classification-using-logistic-regression/
│
├── data/
│   └── Breast_cancer_wisconsin_dataset.csv
│
├── notebooks/
│   └── Task4_Breast_Cancer_Classification_Using_Logistic_Regression.ipynb
│
├── reports/
│   └── Task4_Breast_Cancer_Classification_Report.pdf
│
├── README.md

```

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
    git clone https://github.com/diyab6804-gh/Breast-cancer-classification-using-logistic-regression.git
   
2. Install dependencies
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Jupyter Notebook
   ```
   jupyter notebook

---

## 🏁 Conclusion

This project demonstrates a complete and professional machine learning workflow for healthcare classification problems. By combining logistic regression with advanced evaluation and threshold optimization, the developed model achieves high reliability and clinical relevance, making it suitable for real-world diagnostic support systems.

---

## 👩‍💻 Author

Patel Diya B

AI/ML Intern
