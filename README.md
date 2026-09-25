# Montagnini-IntrusionDetectionUNSW-NB15

Machine learning project for detecting and classifying malicious network traffic.

## Objectives

The project addresses two classification tasks on the UNSW-NB15 network traffic dataset:
- **Binary classification**: detect whether traffic is normal or malicious (`label` feature)
- **Multiclass classification**: identify the specific attack category (`attack_cat` feature) among 9 possible types (Generic, Exploits, Fuzzers, DoS, Reconnaissance, Analysis, Backdoor, Shellcode, Worms)

## Methodology

The project follows these steps: Exploratory Data Analysis (EDA), preprocessing (decoupling, encoding, skewness correction, scaling), attribute selection (SelectKBest vs PCA) and classification (Decision Tree and Random Forest, tuned with GridSearchCV).

## Results

- **Binary classification**: F1 = 0.92 (Random Forest)
- **Multiclass classification**: Macro F1 = 0.57 (Random Forest)

## Repository structure

- `notebooks/`: analysis and modeling notebooks (see README in subfolder for additional details)
- `data/`: raw, processed and reduced datasets
- `doc/`: Beamer presentation and generated assets (e.g., plots, matrices)

## References

- [Kaggle competition: Advanced AI for Cybersecurity: Intrusion Detection with UNSW-NB15](https://www.kaggle.com/competitions/advanced-ai-for-cybersecurity-intrusion-detection-with-unsw-nb-15/overview)
