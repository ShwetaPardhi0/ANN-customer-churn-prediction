# 🧠 Customer Churn Prediction using ANN

This project uses an **Artificial Neural Network (ANN)** to predict whether a customer is likely to leave the bank (churn) based on their demographic and account activity data. It is trained on the well-known `Churn_Modelling.csv` dataset.

---

## 🚀 What It Does

- Loads customer data from a public dataset
- Preprocesses the data: encoding, scaling, and splitting
- Builds a multi-layer ANN using **Keras**
- Trains the model and evaluates performance
- Visualizes accuracy and loss over epochs

---

## 📊 Dataset

The dataset contains records of **10,000 bank customers** with the following features:

- 📌 Features include:
  - Geography, Gender, Age, Balance
  - Credit Score, Tenure, Number of Products
  - Has Credit Card, Is Active Member, Estimated Salary

- 🎯 **Target variable**: `Exited`  
  - `1` = Customer churned  
  - `0` = Customer stayed with the bank

  ---

## 🧠 Model Overview

- **Architecture**: Feedforward ANN with input, hidden, and output layers
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Evaluation Metric**: Accuracy

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn

---

## 🧪 How to Run

1. Clone the repository:
```bash
git clone https://github.com/shwetapardhi0/ANN-customer-churn-prediction.git
cd ANN-customer-churn-prediction
