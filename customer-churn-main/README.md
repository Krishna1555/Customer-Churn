
# Bank Churn Prediction

An end-to-end machine learning project that predicts whether a bank customer is likely to leave. The model is deployed using Flask, with MLflow for experiment tracking.

## Features
- Data preprocessing and feature engineering
- SMOTE for handling imbalanced data
- Model training and evaluation
- MLflow experiment tracking
- Flask API for real-time predictions

## Tech Stack
Python, Pandas, Scikit-learn, Flask, MLflow, SMOTE, Conda

## Installation

```bash
git clone https://github.com/Debopam-Pritam2014/customer-churn.git
cd customer-churn

conda create -n churn_prediction python=3.10
conda activate churn_prediction

pip install -r requirements.txt
```

## Run the Application

```bash
python app.py
```

Open http://127.0.0.1:5000/ in your browser.

Use the `/predict` endpoint to submit customer details and receive a churn prediction.

## Model Performance

| Metric | Score |
|---|---:|
| Accuracy | 86% |
| Precision | 66% |
| Recall | 62% |
| F1-score | 60% |

**Best Model:** Gradient Boosting Classifier
