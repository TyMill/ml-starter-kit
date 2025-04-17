# K-Nearest Neighbors (KNN)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/knn/knn_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**K-Nearest Neighbors (KNN)** is a non-parametric, instance-based learning algorithm used for both classification and regression.  
It predicts the output for a sample based on the majority vote of its `k` closest training samples.

---

## 🔍 What is KNN?

- Stores the **entire training set** in memory  
- Uses **distance metrics** (e.g. Euclidean) to find neighbors  
- Simple but powerful, especially in low-dimensional data  
- Sensitive to **feature scaling**

---

## ✅ Advantages

- Intuitive and easy to implement  
- No training phase (lazy learner)  
- Effective on small and well-separated datasets  
- Adaptable to classification and regression

## ❌ Disadvantages

- Slow prediction time for large datasets  
- Sensitive to noise and irrelevant features  
- Requires feature scaling  
- Struggles in high-dimensional spaces

---

## 🧪 What’s Inside the Tutorial

- 🍷 Wine dataset classification  
- ⚙️ Standard scaling of features  
- 📊 Accuracy, confusion matrix, and classification report  
- 🔁 Cross-validation for optimal `k`

📘 Notebook: [`knn_tutorial.ipynb`](./knn_tutorial.ipynb)

---

## 📂 File Structure

- `knn_tutorial.ipynb` – Full KNN tutorial notebook  
- `README.md` – This file  
- `references.md` – Learning resources and tutorials

---

## 📚 Recommended Reading

- [scikit-learn: KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)  
- [Wikipedia: KNN](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)  
- [TDS: Understanding KNN](https://towardsdatascience.com/understanding-k-nearest-neighbor-knn-6a6e71d0d593)

---

## 🚀 Try It Yourself

- Tune `k` using cross-validation  
- Try other distance metrics (e.g. Manhattan, cosine)  
- Compare with SVM or Decision Tree  
- Use PCA for dimensionality reduction

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
