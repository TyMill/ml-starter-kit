# Logistic Regression

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/logistic_regression/logistic_regression_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Logistic Regression** is a fundamental classification algorithm used for binary and multi-class problems.  
It models the probability that a given input belongs to a particular class using the logistic (sigmoid) function.

---

## 🔍 What is Logistic Regression?

Logistic regression outputs **probabilities** between 0 and 1 by applying a sigmoid function to a linear combination of input features:

$$
P(y = 1|x) = \\frac{1}{1 + e^{-z}} = \\frac{1}{1 + e^{- (\\beta_0 + \\beta_1 x_1 + \\dots + \\beta_n x_n)}}
$$

Where:
- `xᵢ`: input features  
- `βᵢ`: learned coefficients  
- `z`: linear combination of features  
- `P(y = 1 | x)`: probability of class 1 given inputs

---

## 🧠 When to Use

- Binary classification tasks (e.g. spam vs. not spam)
- Interpretable and explainable models
- Real-time applications (fast inference)
- When outputs should represent probabilities

---

## ✅ Advantages

- Probabilistic interpretation
- Fast and simple to implement
- Works well with linearly separable classes
- Easily extendable to multi-class (softmax)

## ❌ Disadvantages

- Assumes linear decision boundary
- Sensitive to multicollinearity
- Poor performance on highly non-linear problems
- Can underfit complex data

---

## 🧪 What’s Inside the Tutorial

This notebook includes:
- 📈 Visualization of decision boundary using 2D synthetic data
- 🔢 Manual coefficient inspection
- 📊 Real-world dataset: Breast Cancer (Wisconsin Diagnostic)
- 📉 Metrics: Confusion Matrix, Accuracy, Precision, Recall, ROC-AUC
- 📐 ROC Curve plotting and interpretation

📘 Notebook: [`logistic_regression_tutorial.ipynb`](./logistic_regression_tutorial.ipynb)

---

## 📂 File Structure

- `logistic_regression_tutorial.ipynb` – Full implementation
- `README.md` – This file
- `references.md` – Key learning resources

---

## 📚 Recommended Reading

- [scikit-learn: Logistic Regression](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)
- [StatQuest: Logistic Regression](https://www.youtube.com/watch?v=yIYKR4sgzI8)
- [Wikipedia: Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression)

---

## ✨ Example Visualization

![Logistic Curve](https://upload.wikimedia.org/wikipedia/commons/6/6d/Logistic-curve.svg)

---

## 🧠 Try It Yourself

- Tune hyperparameters (e.g. regularization `C`)
- Use `solver='liblinear'` for small datasets
- Add polynomial features for non-linearity
- Try `LogisticRegressionCV` for cross-validated models

---

Created with ❤️ by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
