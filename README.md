# Customer Churn Prediction

## Project Overview

This Machine Learning project predicts whether a telecom customer is likely to churn using Logistic Regression.

The project includes:
- Data preprocessing
- Exploratory Data Analysis
- Feature encoding
- Model training
- Model evaluation
- Visualization using Confusion Matrix

---

## Dataset Information

Dataset: Telco Customer Churn Dataset

Total Records: 7043  
Total Features: 21

Target Variable:
- Churn

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Encoding Categorical Variables
5. Train-Test Split
6. Logistic Regression Model Training
7. Model Evaluation
8. Confusion Matrix Visualization
9. Model Saving using Pickle

---

## Model Performance

Accuracy Score:
```python
0.8239
---

## Confusion Matrix

![Confusion Matrix](screenshots/confusion_matrix.png)

---

## Project Structure

```bash
customer-churn-prediction/
│
├── dataset/
│   └── churn.csv
│
├── notebook/
│   └── churn_prediction.ipynb
│
├── model/
│   └── customer_churn_model.pkl
│
├── screenshots/
│   └── confusion_matrix.png
│
├── requirements.txt
│
└── README.md
```

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yasirsheikh07/customer-churn-prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run:
```bash
notebook/churn_prediction.ipynb
```

---

## Future Improvements

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Streamlit Deployment
- Interactive Dashboard

---

## Author

Mohammad Yasir Sheikh

GitHub:
https://github.com/yasirsheikh07
