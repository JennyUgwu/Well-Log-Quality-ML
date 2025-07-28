# Well Log Quality Control using Machine Learning

This repository contains the code and supporting files for my MSc dissertation project titled:

**"Machine Learning for Automated Quality Control: Predicting Borehole Integrity from Petrophysical Well Logs"**

## 📁 Contents

- `Msc-Dissertation.Automatic-Quality-Control.ipynb`: Main Jupyter Notebook used for data analysis, preprocessing, and model development
- `requirements.txt`: (Optional) Python dependencies

## 🎯 Objective

The goal was to assess borehole integrity by classifying poor-quality intervals using petrophysical logs from the FORCE 2020 dataset. The project employed Isolation Forest for anomaly detection and XGBoost for supervised classification.

## 📊 Features Used

- GR, DEN, NEU, RDEP, PEF, PHIF

## ⚙️ Methods

- Data cleaning and outlier removal (Z-score, Isolation Forest)
- Missing value imputation (Iterative Imputer)
- Threshold-based quality labeling
- Model tuning and SHAP explainability

## 🛠️ Tools

- Python
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn
- SHAP

## 📎 Report Link

Final report submitted as part of the MSc Petroleum Data Management programme at the University of Aberdeen. To view the notebook:

👉 [Click here to view the notebook](https://github.com/JennyUgwu/Well-Log-Quality-ML/blob/main/Msc-Dissertation.Automatic-Quality-Control.ipynb)

---

