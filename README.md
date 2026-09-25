# Customer Churn Prediction System

A machine learning-based web application that predicts whether a customer is likely to churn based on customer and subscription-related information.

## 🚀 Features

* Customer churn prediction using Machine Learning
* Interactive Streamlit web interface
* Customer data preprocessing
* Handles missing values and categorical features
* Displays churn prediction results
* Trained model saved using Joblib
* Easy-to-use interface for live demonstration

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Joblib**
* **Streamlit**
* **Matplotlib / Seaborn**

## 📁 Project Structure

```text
customer_churn_prediction_system/
│
├── streamlit_app.py
├── requirements.txt
├── README.md
│
├── models/
│   └── churn_model.joblib
│
├── data/
│   └── customer_churn.csv
│
└── notebooks/
    └── customer_churn_prediction.ipynb
```

## 📊 Dataset

The project uses customer-related information such as:

* Gender
* Subscription Type
* Contract Length
* Customer details
* Subscription-related information
* Churn status

The target variable is **Churn**:

* `0` → Customer is not likely to churn
* `1` → Customer is likely to churn

## 🤖 Machine Learning Model

The machine learning pipeline includes:

1. Data loading
2. Data cleaning
3. Missing-value handling
4. Categorical data preprocessing
5. Feature preparation
6. Model training
7. Model evaluation
8. Model serialization using Joblib
9. Streamlit deployment

The trained model is stored at:

```text
models/churn_model.joblib
```

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Sudalai-sanjay/customer_churn_prediction_system.git
```

### 2. Open the project

```bash
cd customer_churn_prediction_system
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run streamlit_app.py
```

The application will open in your browser.

## 🖥️ Streamlit Application

The Streamlit application allows users to enter customer information and receive a churn prediction through an interactive interface.

## 📈 Project Workflow

```text
Customer Data
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
Machine Learning Model
      ↓
Churn Prediction
      ↓
Streamlit Web Application
```

## 🎯 Objective

The objective of this project is to use machine learning to identify customers who may be likely to churn. Such predictions can help businesses analyze customer behavior and support customer-retention strategies.

## 👨‍💻 Author

**Sudalai R**

GitHub: https://github.com/Sudalai-sanjay

## 📄 License

This project is developed for educational and demonstration purposes.
