# Random Forest

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/random_forest/random_forest_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Random Forest** is a versatile and powerful ensemble method that combines multiple decision trees.  
It is one of the most widely used algorithms for classification and regression tasks on tabular data.

---

## 🔍 What is Random Forest?

- Trains a large number of **decision trees**  
- Each tree is trained on a **bootstrap sample** of the data  
- Predictions are made by **majority vote** (classification) or **averaging** (regression)  
- Helps reduce overfitting and variance

---

## ✅ Advantages

- Handles high-dimensional data well  
- Built-in feature importance  
- Reduces overfitting via ensemble averaging  
- Works well with default parameters

## ❌ Disadvantages

- Slower inference time with many trees  
- Less interpretable than individual trees  
- Can still overfit if not tuned

---

## 🧪 What’s Inside the Tutorial

- 🏥 Classification on Breast Cancer dataset  
- 📈 Confusion matrix, classification report  
- 🌲 Feature importance ranking  
- 🔁 Cross-validation and accuracy reporting

📘 Notebook: [`random_forest_tutorial.ipynb`](./random_forest_tutorial.ipynb)

---

## 📂 File Structure

- `random_forest_tutorial.ipynb` – Main tutorial notebook  
- `README.md` – This file  
- `references.md` – Additional reading and resources

---

## 📚 Recommended Reading

- [scikit-learn: RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)  
- [Wikipedia: Random Forest](https://en.wikipedia.org/wiki/Random_forest)  
- [TDS: Random Forest Explained](https://towardsdatascience.com/the-random-forest-algorithm-d457d499ffcd)

---

## 🚀 Try It Yourself

- Tune `n_estimators`, `max_depth`, and `max_features`  
- Compare Random Forest with Gradient Boosting  
- Visualize tree structures using `export_graphviz`  
- Try regression with `RandomForestRegressor`

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
