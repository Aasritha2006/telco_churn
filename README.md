# Telco Customer Churn Prediction (Jupyter Notebook)

## Files
- `Telco_Customer_Churn_Prediction.ipynb`: Main Jupyter Notebook with code and explanations.
- `requirements.txt`: Required Python packages.
- `sample_unseen_customers.csv`: Example customer records for trying predictions.

## Dataset setup
1. Download the CSV from https://www.kaggle.com/datasets/blastchar/telco-customer-churn
2. Place `WA_Fn-UseC_-Telco-Customer-Churn.csv` in the same folder as the notebook.
3. Open the notebook and choose **Run All**.

## Install packages
```bash
pip install -r requirements.txt
```

## Start Jupyter
```bash
jupyter notebook
```

The notebook trains Logistic Regression, reports Accuracy/Precision/Recall/F1-score, shows a confusion matrix, predicts unseen records, and saves test predictions to `churn_predictions.csv`.
