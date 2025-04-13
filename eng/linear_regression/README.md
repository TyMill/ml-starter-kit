# Linear Regression

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tymill/ml-starter-kit/blob/main/eng/linear_regression/linear_regression_tutorial.ipynb)
[![Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/kernels)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

Linear Regression is one of the most fundamental and widely used algorithms in supervised machine learning.  
It models the relationship between a dependent variable (target) and one or more independent variables (features) by fitting a linear equation.

---

## 🔍 What is Linear Regression?

Linear regression assumes that the target variable can be expressed as a linear combination of the input features:

### Simple Linear Regression:

$$
y = \\beta_0 + \\beta_1 x + \\epsilon
$$

### Multiple Linear Regression:

$$
y = \\beta_0 + \\beta_1 x_1 + \\beta_2 x_2 + \\dots + \\beta_n x_n + \\epsilon
$$

**Where:**

- \( y \): dependent variable  
- \( x_i \): independent variables  
- \( \\beta_i \): coefficients  
- \( \\epsilon \): error term

---

## 🧠 When to Use

- Predicting a **continuous** numerical output
- When the relationship between variables is approximately **linear**
- When **interpretability** matters (understanding feature impact)

---

## ✅ Advantages

- Simple and fast
- Interpretable
- Works well for linearly separable data
- Good baseline model

## ❌ Disadvantages

- Assumes linear relationship
- Sensitive to outliers
- Multicollinearity between features can distort results
- Underperforms on complex nonlinear data

---

## 🧪 What’s Inside the Tutorial

This notebook includes:
- Manual implementation using NumPy
- Residual analysis and visualization
- scikit-learn implementation
- Real-world example using **California Housing** dataset
- Feature importance plot
- Error metrics: **MAE**, **MSE**, **RMSE**, **R²**

📘 Notebook: [`linear_regression_tutorial.ipynb`](./linear_regression_tutorial.ipynb)

---

## 📂 File Structure

- `linear_regression_tutorial.ipynb` – Full implementation
- `README.md` – You're reading it 😉
- `references.md` – Further reading and useful links

---

## 📚 Recommended Reading

- [Scikit-learn documentation on Linear Regression](https://scikit-learn.org/stable/modules/linear_model.html#ordinary-least-squares)
- [StatQuest: Linear Regression](https://www.youtube.com/watch?v=nk2CQITm_eo)
- [Coursera – Machine Learning (Andrew Ng)](https://www.coursera.org/learn/machine-learning)

---

## ✨ Example Output

![Regression Example](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Linear_regression.svg/512px-Linear_regression.svg.png)

---

## 🧠 Try It Yourself

Run the notebook and modify the data or model parameters.  
Experiment with:
- Polynomial features
- Regularization (Ridge, Lasso)
- Residual plots on new data
- Feature selection

---

Created with 💙 by **Tymoteusz Miller** — part of the [ML Cheatsheet Repo](../../README.md)
