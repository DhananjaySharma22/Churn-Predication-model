# 🛑 Churn Prediction Model  
This repository contains a **Churn Prediction Model** built using **Python** in **Google Colab**. The project covers **EDA (Exploratory Data Analysis)**, **data preprocessing**, **SMOTE-ENN for class balancing**, and **model building with Decision Tree and Random Forest** for result comparison — all implemented in a single `.ipynb` file.

---

## 🚀 Project Overview  
This project aims to predict customer churn by comparing the performance of two machine learning models:  
1. **EDA & Preprocessing:**  
   - Data cleaning, handling missing values, and feature engineering.  
   - Visualizing key trends and correlations.  
2. **Class Balancing with SMOTE-ENN:**  
   - Applied **SMOTE-ENN** to handle class imbalance by oversampling the minority class and cleaning noisy samples.  
3. **Model Building & Comparison:**  
   - **Decision Tree** and **Random Forest** models were trained.  
   - Compared their accuracy, precision, recall, F1-score, and AUC-ROC.  
4. **Model Evaluation & Testing:**  
   - Displayed confusion matrices, ROC curves, and classification reports.  
   - Included code to test the models on new/unseen data.

---

## ⚙️ Technologies & Libraries Used  
- **Platform:** Google Colab  
- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` → Data manipulation and preprocessing  
  - `matplotlib`, `seaborn` → Data visualization  
  - `sklearn` → Model building and evaluation  
  - `imblearn` → SMOTE-ENN for class balancing  

---

## 📊 Dataset  
- The dataset contains customer information with features such as tenure, monthly charges, contract type, and churn status.  
- It is publicly available and used for educational purposes.  

---

## 🔥 How to Run  
1. **Open the Colab notebook:**  
   - Click the link to open the `.ipynb` file in Google Colab.  
2. **Connect to Google Drive (if needed)** to access external datasets.  
3. **Install missing libraries** (if required):  
```python
!pip install imbalanced-learn
