# Customer Churn Prediction 📉

A machine learning project to predict whether a customer will churn (leave) based on their demographic, account, and service usage information.

## 🔍 Project Overview

Customer churn is a major issue for subscription-based businesses. This project analyzes customer data from a telecom company to predict churn using various classification models. The goal is to help businesses identify at-risk customers and take proactive measures to retain them.

## 📂 Dataset

The dataset contains 7,043 customer records with 21 features including:

- Demographics (gender, senior citizen, etc.)
- Services signed up for (internet, streaming, etc.)
- Account information (tenure, billing method, charges)
- Target column: `Churn` (Yes/No)

### Sample Columns

| Feature           | Description                           |
|------------------|---------------------------------------|
| `gender`         | Gender of the customer                |
| `SeniorCitizen`  | Whether the customer is a senior      |
| `tenure`         | Number of months the customer stayed  |
| `Contract`       | Contract type (Month-to-month, etc.)  |
| `PaymentMethod`  | Payment method used                   |
| `Churn`          | Whether the customer left (Yes/No)    |

📌 `TotalCharges` is an object and needs conversion to numeric before training.

## ⚙️ Tech Stack

- **Python**
- **Pandas**, **NumPy** for data handling
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for machine learning models
- **Jupyter Notebook** for exploratory data analysis and model training

## 🧠 Models Used

- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

## 📈 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/DINAKAR-S/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📊 Results

Best model: **Random Forest**  
Accuracy: ~85%  
ROC-AUC: ~0.88  

## 📌 Future Improvements

- Feature engineering (combine/categorize features)
- Handle class imbalance with SMOTE or similar
- Deploy as a web app using Flask or Streamlit

⭐️ Feel free to star this repo if you found it helpful!
```
