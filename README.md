# GlucoGuard — Diabetes Prediction Project

## 🧠 Overview  
This project is a Python-based demonstration of training a binary classifier to predict diabetes using health metrics. The model is trained on a publicly available dataset and evaluated to measure its performance.

## 📦 What’s Included
- Loading the dataset from a raw GitHub link (no manual file uploads needed)  
- Exploring the first few rows of the data using `print()`  
- Splitting into **training** and **test** sets with stratification (`train_test_split`)  
- Applying **feature scaling** using `StandardScaler`  
- Training a **Support Vector Machine (SVM)** model with a linear kernel  
- Making predictions and computing **accuracy** as an evaluation met

## ⚙️ How to Run  
1. Open the notebook `Diabetes_Prediction.ipynb` in Google Colab or Jupyter.  
2. Make sure you have the required libraries installed: `pandas`, `scikit-learn`.  
3. Run all cells in order — the dataset loads automatically and the model trains and evaluates.

## 🎯 What You’ll Learn  
- Loading data directly from GitHub using `pd.read_csv`  
- Splitting data with `train_test_split` while preserving class balance  
- Scaling features with `StandardScaler`  
- Training and evaluating an SVM model using accuracy as a metric
