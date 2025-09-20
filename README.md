# Logistic-regression-model
# Logistic Regression Model

This repository demonstrates how to build, train, and evaluate a **Logistic Regression** classification model using Python. It uses a real dataset related to weather conditions to predict outcomes, with steps including data exploration, preprocessing, model training, saving/loading, and evaluation.

---

## 🔍 What’s Inside

- `Logistic Regression sample.ipynb` — A Jupyter notebook that walks through:
  - Loading the `weatherAUS.csv` dataset  
  - Exploring and visualizing the data  
  - Preprocessing: handling missing values, encoding categorical variables, feature selection / scaling (if applicable)  
  - Splitting into train/test sets  
  - Fitting a Logistic Regression classifier  
  - Evaluating model performance (accuracy, confusion matrix, ROC / AUC if included)  
  - Saving the trained model as `aussie_rain.joblib`  

- `weatherAUS.csv` — The dataset used for training / testing.  
- `aussie_rain.joblib` — Serialized trained model, so you can load it and use it without retraining.  

---

## 📂 Requirements

- Python 3.x  
- Key libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - (optional) `matplotlib` / `seaborn` for visualizations  
  - `joblib` for saving / loading models
