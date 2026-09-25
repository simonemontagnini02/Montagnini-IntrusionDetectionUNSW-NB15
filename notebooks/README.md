# Notebooks — Intrusion Detection on UNSW-NB15

## Prerequisites
- Python 3.x
- Dependencies listed in `requirements.txt`


## Installation
```bash
pip install -r requirements.txt
```

## Data
The file `UNSW_NB15_training-set.parquet`is included in the `../data/` folder.

> As per course instructions, only the training set is used for this project.


## Notebooks (execution order)

| Notebook | Description |
|---|---|
| `01_eda.ipynb` | Exploratory Data Analysis |
| `02_processing_feature_engineering.ipynb` | Data cleaning, encoding, skewness correction |
| `03_attribute_selecting.ipynb` | Feature selection (SelectKBest) and dimensionality reduction (PCA) |
| `04_classification_binary.ipynb` | Binary classification (label): Decision Tree vs Random Forest |
| `05_classification_multiclass.ipynb` | Multiclass classification (attack_cat): Decision Tree vs Random Forest |
| `06_evaluation_comparison.ipynb` | Final evaluation, confusion matrices, feature importance, conclusions |


## How to run
1. Activate Jupyter environment and install dependencies.
2. Ensure the dataset is placed in `../data/` directory.
3. Run notebooks in order.
