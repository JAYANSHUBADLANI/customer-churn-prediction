# Customer Churn Prediction

End-to-end machine learning pipeline to predict telecom customer churn using the IBM Telco Customer Churn dataset. Covers exploratory analysis, XGBoost classification, SHAP explainability, and cohort-level revenue at risk analysis.

## Project Structure

```
customer-churn-prediction/
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_model.ipynb
│   ├── 03_shap.ipynb
│   └── 04_cohort.ipynb
├── visuals/
├── results/
│   └── metrics.json
└── requirements.txt
```

## Results

| Metric | Score |
|---|---|
| Accuracy | 0.7594 |
| F1 (weighted) | 0.7701 |
| ROC-AUC | 0.8362 |
| CV ROC-AUC (5-fold) | 0.8401 ± 0.011 |

## How to Run

```bash
git clone https://github.com/JAYANSHUBADLANI/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
jupyter notebook
```

Run notebooks in order: `01_eda` → `02_model` → `03_shap` → `04_cohort`. Plots save to `/visuals`, metrics to `/results/metrics.json`.

## Dataset

[IBM Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn): 7,043 customers, 21 features. Target variable: `Churn` (Yes/No).

**Author:** Jayanshu Badlani | [GitHub](https://github.com/JAYANSHUBADLANI) | [LinkedIn](https://linkedin.com/in/jayanshu-badlani)
