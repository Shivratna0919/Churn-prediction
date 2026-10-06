# Customer Churn Prediction System

A Machine Learning project that predicts whether a bank customer is likely to **stay or exit** using a **Random Forest Classifier** and a Streamlit web application.

## 🚀 Features

- Customer churn prediction
- Churn & stay probability
- Model confidence
- Interactive Streamlit UI
- Customer information dashboard
- Random Forest Machine Learning model

## 🧠 ML Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Feature Encoding
   ↓
StandardScaler
   ↓
Random Forest
   ↓
Model Evaluation
   ↓
Streamlit Prediction App
```

## 📊 Model

- **Algorithm:** Random Forest Classifier
- **Problem:** Binary Classification
- **Target:** `Exited`
- **Features:** 11
- **Train/Test Split:** 80/20
- **Scaler:** StandardScaler
- **Recorded Accuracy:** 86.65%

### Features

```text
CreditScore
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Germany
Spain
Male
```

## 🗂️ Project Structure

```text
Customer-Churn-Prediction/
│
├── app.py
├── random_forest_churn_model.pkl
├── scaler.pkl
├── Churn_Modelling.csv
├── Python_Implementation_for_churn_prediction.ipynb
├── requirements.txt
└── README.md
```

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

Then open the Streamlit URL shown in the terminal.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest
- StandardScaler
- Streamlit

## 🎯 Future Scope

- Batch CSV prediction
- Prediction history
- Customer analytics dashboard
- Feature importance / SHAP
- Cloud deployment

## 📌 Purpose

This project demonstrates an end-to-end Machine Learning workflow for customer churn prediction and an interactive web-based prediction system.

**For educational and project demonstration purposes.**
