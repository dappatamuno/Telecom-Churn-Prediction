# Telecom-Churn-Prediction
📌 Project Title: Telecom Customer Churn Prediction

Predicting customer churn using machine learning and deep learning techniques.

📌 Project Description

Objective: Predict whether a telecom customer will churn (leave the service) based on features like contract type, tenure, and monthly charges.

Models Used: Logistic Regression, Random Forest, SVM, AdaBoost, XG Boost, TensorFlow DNN.

Best Model: XG Boost (82.94% accuracy) outperformed others.

## Dataset Setup
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).
2. Place `WA_Fn-UseC_-Telco-Customer-Churn.csv` in the `data/` folder.

📌 Key Insights from EDA

High Churn Risk Factors:

Month-to-month contracts.

High monthly charges.

Lack of online security/tech support.

Low Churn Factors:

Long-term contracts (2-year).

Higher tenure (long-term customers).

📌 Model Performance Comparison

Model	Accuracy
Logistic Regression	65.96%
Random Forest	65.96%
SVM	82.94%
AdaBoost	82.94%
XG Boost	82.94%
TensorFlow DNN	81.17%

📌 How to Run the Code

Clone the repository:
bash
git clone https://github.com/dappatamuno/telecom-churn-prediction.git
cd telecom-churn-prediction
Install dependencies:

bash
pip install -r requirements.txt
Run Jupyter notebooks:

bash
jupyter notebook

📌 Dependencies

List all required libraries in requirements.txt:
numpy==1.21.5
pandas==1.3.5
scikit-learn==1.0.2
matplotlib==3.5.1
seaborn==0.11.2
xgboost==1.6.1
tensorflow==2.10.0
jupyter==1.0.0

📌 Future Improvements

Hyperparameter tuning for Random Forest/DNN.
Deploy the best model (XG Boost) using Flask/FastAPI.
Implement SHAP/LIME for explainability.
