# Customer Churn Prediction using Machine Learning

## Project Overview

This project predicts whether a telecom customer is likely to churn using various machine learning classification algorithms. The goal is to help businesses identify customers who are at risk of leaving so that proactive retention strategies can be implemented.

---

## Problem Statement

Customer churn is one of the biggest challenges faced by telecom companies. By analyzing customer information such as tenure, monthly charges, contract type, and payment method, this project builds predictive models to classify customers as churned or retained.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

- Total Records: 7,043
- Features: 20 original features
- Target Variable: Churn (Yes/No)

---

## Project Workflow

1. Data Loading and Inspection
2. Exploratory Data Analysis (EDA)
3. Data Visualization
4. Data Preprocessing
5. Model Building
6. Model Evaluation and Comparison
7. Saving the Best Model

---

## Data Preprocessing

- Checked for missing values
- Filled missing values in `TotalCharges`
- Encoded categorical variables using One-Hot Encoding
- Converted target variable (Churn) into binary format
- Removed unnecessary features (`customerID`)
- Split dataset into training and testing sets
- Applied feature scaling where required

---

## Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

---

## Best Performing Model

The Random Forest classifier achieved the best overall performance based on the evaluation metrics and was selected as the final model.

The trained model has been saved as:

```
models/random_forest_model.pkl
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Project Structure

```
customer-churn-prediction/
│
├── data/
├── images/
├── models/
│   └── random_forest_model.pkl
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

1. Clone the repository.

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```
notebooks/Customer_Churn_Prediction.ipynb
```

4. Run all cells.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- ROC-AUC analysis
- Confusion matrix visualization
- Deploy the model using Flask, FastAPI, or Streamlit

---

## Author

**Ashish Pradhan**

Artificial Intelligence & Machine Learning Intern