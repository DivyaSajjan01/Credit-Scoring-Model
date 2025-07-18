# Credit-Scoring-Model

This repository contains a complete machine learning pipeline to predict the probability of credit default using financial and demographic information. The project is built around the Kaggle "Give Me Some Credit" dataset.

## 📌 Project Overview

The goal of this project is to create a predictive model that estimates the likelihood of a person experiencing financial distress (default) in the next two years. This can be helpful for banks or financial institutions to assess credit risk.

## 📂 Files

- `Divya_Credit_Scoring_Model.ipynb` — Full Jupyter notebook with preprocessing, visualization, model building, and prediction.
- `requirements.txt` — List of Python dependencies to reproduce the project.
- `README.md` — You're reading it :)

## 📊 Dataset

The dataset includes:
- Demographic info like age, dependents
- Financial metrics such as debt ratio, monthly income, number of credit lines, late payments, etc.
- Target variable: `SeriousDlqin2yrs` (1 = default, 0 = non-default)

Data source: [Kaggle - Give Me Some Credit](https://www.kaggle.com/c/GiveMeSomeCredit)

## 🔧 Technologies Used

- Python 3.11+
- Pandas
- NumPy
- Seaborn / Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🧠 Models Used

- **Random Forest Classifier**
- GridSearchCV for tuning
- Feature binning and one-hot encoding for preprocessing
