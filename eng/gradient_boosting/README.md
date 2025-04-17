# Gradient Boosting

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/gradient_boosting/gradient_boosting_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Gradient Boosting** is a powerful machine learning technique that builds an ensemble of weak learners (typically decision trees) in a sequential, stage-wise manner.  
Each new model focuses on the residuals of the previous model.

---

## 🔍 What is Gradient Boosting?

- Combines **multiple models** to reduce bias and variance  
- Uses **gradient descent** to minimize loss  
- Can be used for classification, regression, and ranking  
- Popularized by **XGBoost**, **LightGBM**, and **CatBoost**

---

## ✅ Advantages

- Excellent accuracy in many applications  
- Handles different types of data  
- Built-in feature importance  
- Can be tuned for speed, size, and performance

## ❌ Disadvantages

- Slower to train than simpler models  
- Sensitive to hyperparameters  
- Can overfit if not properly tuned

---

## 🧪 What’s Inside the Tutorial

- 🏥 Classification on Breast Cancer dataset  
- 🔍 Confusion matrix and classification report  
- 📊 Feature importance chart  
- 🔁 Cross-validation and learning rate tuning

📘 Notebook: [`gradient_boosting_tutorial.ipynb`](./gradient_boosting_tutorial.ipynb)

---

## 📂 File Structure

- `gradient_boosting_tutorial.ipynb` – Main tutorial notebook  
- `README.md` – This file  
- `references.md` – Further reading and resources

---

## 📚 Recommended Reading

- [scikit-learn: GradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)  
- [Wikipedia: Gradient Boosting](https://en.wikipedia.org/wiki/Gradient_boosting)  
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/)

---

## 🚀 Try It Yourself

- Compare `GradientBoostingClassifier` vs `XGBClassifier`  
- Adjust `learning_rate`, `n_estimators`, `max_depth`  
- Apply to your own tabular datasets  
- Try regression with `GradientBoostingRegressor`

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
