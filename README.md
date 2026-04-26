# Customer Churn Prediction

End-to-end machine learning pipeline to predict telecom customer churn using the IBM Telco Customer Churn dataset. Includes exploratory data analysis, XGBoost classification, SHAP-based explainability, and cohort-level revenue at risk analysis.

---

## Project Structure

```
customer-churn-prediction/
├── notebooks/
│   ├── 01_eda.ipynb          # Exploratory Data Analysis
│   ├── 02_model.ipynb        # XGBoost training & evaluation
│   ├── 03_shap.ipynb         # SHAP feature explainability
│   └── 04_cohort.ipynb       # Cohort analysis & revenue at risk
├── visuals/                  # All saved plots (PNG)
├── results/
│   └── metrics.json          # Model evaluation metrics
├── requirements.txt
└── README.md
```

---

## Tech Stack

| Category | Tools |
|---|---|
| Data manipulation | pandas, numpy |
| Machine learning | scikit-learn, XGBoost |
| Explainability | SHAP |
| Visualization | matplotlib, seaborn, plotly |
| Environment | Jupyter, Python 3.10+ |

---

## Results

| Metric | Score |
|---|---|
| Accuracy | — |
| F1 Score (weighted) | — |
| ROC-AUC | — |
| Precision | — |
| Recall | — |

> Results populated after running `02_model.ipynb`

---

## How to Run

### 1. Clone the repo
```bash
git clone https://github.com/JAYANSHUBADLANI/customer-churn-prediction.git
cd customer-churn-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run notebooks in order
```bash
jupyter notebook
```
Open and run:
1. `notebooks/01_eda.ipynb` — EDA and visualizations
2. `notebooks/02_model.ipynb` — Model training and evaluation
3. `notebooks/03_shap.ipynb` — SHAP explainability
4. `notebooks/04_cohort.ipynb` — Cohort and revenue analysis

All plots are saved to `/visuals`, metrics to `/results/metrics.json`.

---

## Dataset

**IBM Telco Customer Churn** — 7,043 customers, 21 features including demographics, account info, and service subscriptions. Target variable: `Churn` (Yes/No).

---

## Author

**Jayanshu Badlani**
[GitHub](https://github.com/JAYANSHUBADLANI) | [LinkedIn](https://linkedin.com/in/jayanshu-badlani)
