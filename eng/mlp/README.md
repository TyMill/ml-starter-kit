# Multi-Layer Perceptron (MLP)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/mlp/mlp_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

A **Multi-Layer Perceptron (MLP)** is a feedforward neural network with one or more hidden layers and nonlinear activation functions.  
MLPs can learn complex nonlinear patterns in data and are widely used in classification and regression tasks.

---

## 🔍 What is an MLP?

MLPs consist of:
- An input layer  
- One or more hidden layers  
- An output layer  
Each layer consists of neurons that apply:
1. Weighted sum of inputs
2. Non-linear activation (e.g., ReLU, tanh)

They are trained using **backpropagation** and **stochastic gradient descent** (or variants like Adam).

---

## 🧠 When to Use

- Classification or regression on structured/tabular data
- When data is **not linearly separable**
- You need **flexible non-linear models**
- Fast, simple deep learning applications

---

## ✅ Advantages

- Can model **nonlinear** relationships
- Easy to use with `scikit-learn`
- Works with many types of data
- Flexible architecture (depth/width)

## ❌ Disadvantages

- Requires feature scaling (e.g. StandardScaler)
- Sensitive to hyperparameters (e.g., learning rate, hidden size)
- Slower than linear models on small datasets
- Prone to **overfitting** if not regularized

---

## 🧪 What’s Inside the Tutorial

This notebook includes:
- 📊 Classification of moon-shaped data with MLP
- 🔢 Real-world example: Digit recognition
- ⚙️ `MLPClassifier` usage from `sklearn.neural_network`
- 📈 Confusion matrices and classification reports
- 🔍 Hyperparameter tuning with `GridSearchCV`

📘 Notebook: [`mlp_tutorial.ipynb`](./mlp_tutorial.ipynb)

---

## 📂 File Structure

- `mlp_tutorial.ipynb` – Full tutorial
- `README.md` – You’re reading it
- `references.md` – Recommended resources

---

## 📚 Recommended Reading

- [scikit-learn: MLPClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html)
- [Wikipedia: Multilayer Perceptron](https://en.wikipedia.org/wiki/Multilayer_perceptron)
- [Google’s Crash Course – Neural Networks](https://developers.google.com/machine-learning/crash-course/multiclass-neural-networks/softmax)

---

## ✨ Visualization Example

![MLP hidden layers](https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Multilayer_Perceptron.svg/512px-Multilayer_Perceptron.svg.png)

---

## 🧠 Try It Yourself

- Adjust `hidden_layer_sizes` to test deeper/wider networks
- Try different activation functions: `'relu'`, `'tanh'`, `'logistic'`
- Add dropout (use PyTorch or Keras)
- Test regularization via `alpha` parameter

---

Created with 🔥 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
