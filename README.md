🛑 Churn Prediction Model
This repository contains a Churn Prediction Model built using Python in Google Colab. The project covers EDA (Exploratory Data Analysis), data preprocessing, SMOTE-ENN for class balancing, and model building with Decision Tree and Random Forest for result comparison — all implemented in a single .ipynb file.

🚀 Project Overview
This project aims to predict customer churn by comparing the performance of two machine learning models:

EDA & Preprocessing:
Data cleaning, handling missing values, and feature engineering.
Visualizing key trends and correlations.
Class Balancing with SMOTE-ENN:
Applied SMOTE-ENN to handle class imbalance by oversampling the minority class and cleaning noisy samples.
Model Building & Comparison:
Decision Tree and Random Forest models were trained.
Compared their accuracy, precision, recall, F1-score, and AUC-ROC.
Model Evaluation & Testing:
Displayed confusion matrices, ROC curves, and classification reports.
Included code to test the models on new/unseen data.
⚙️ Technologies & Libraries Used
Platform: Google Colab
Language: Python
Libraries:
pandas, numpy → Data manipulation and preprocessing
matplotlib, seaborn → Data visualization
sklearn → Model building and evaluation
imblearn → SMOTE-ENN for class balancing
📊 Dataset
The dataset contains customer information with features such as tenure, monthly charges, contract type, and churn status.
It is publicly available and used for educational purposes.
🔥 How to Run
Open the Colab notebook:
Click the link to open the .ipynb file in Google Colab.
Connect to Google Drive (if needed) to access external datasets.
Install missing libraries (if required):
python
Copy
Edit
!pip install imbalanced-learn
Run the cells sequentially to explore the EDA, apply SMOTE-ENN, build both models, and compare their performance.
Model Testing:
Use the provided test cell to evaluate the models on new data.
✅ Results & Insights
Decision Tree:
Simpler model with faster training time.
May lead to overfitting on complex datasets.
Random Forest:
More robust with better generalization.
Achieved higher accuracy and F1-score in this project.
SMOTE-ENN Impact:
Improved model performance by balancing the classes and reducing noise.
🛠️ Customization & Improvements
Add more models (e.g., XGBoost, Logistic Regression, or SVM) for further comparison.
Use GridSearchCV or RandomizedSearchCV for hyperparameter tuning.
Add interactive visualizations using plotly for better insights.
📌 Acknowledgment
This project was inspired by YouTube tutorials and enhanced with custom modifications.
