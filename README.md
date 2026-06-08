# Tabular Machine Learning Models for Endodontic Treatment Outcome Prediction

This repository contains the tabular-only machine learning code used for predicting endodontic treatment outcomes.

## Files

- `notebooks/tabular_ml_models_clean_github.ipynb`: cleaned Jupyter notebook for tabular ML models
- `requirements.txt`: Python packages needed to run the notebook
- `.gitignore`: files that should not be uploaded to GitHub

## Data

Patient-level data are not included in this repository to protect privacy.

To run the notebook, replace:

```python
pd.read_csv(r"DATA-SOURCE")
```

with the local path to the approved dataset.

## Models included

- Logistic Regression
- Gaussian Naive Bayes
- Random Forest
- XGBoost
- SMOTE versions of the models
- Nested cross-validation
- ROC-AUC, PR-AUC, F1, precision, and recall
