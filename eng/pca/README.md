# Principal Component Analysis (PCA)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/pca/pca_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Principal Component Analysis (PCA)** is a powerful technique for reducing the dimensionality of data.  
It helps in visualizing high-dimensional data, speeding up models, and removing noise while preserving the most important features.

---

## 🔍 What is PCA?

- A **linear transformation** method  
- Projects data onto orthogonal axes called **principal components**  
- Each component maximizes the **variance** in the data  
- Often used before training models or for visualization

---

## ✅ Advantages

- Reduces dimensionality without losing much information  
- Removes multicollinearity between features  
- Improves visualization and interpretability  
- Speeds up model training

## ❌ Disadvantages

- Loses interpretability of transformed features  
- Assumes linear relationships  
- Sensitive to feature scaling

---

## 🧪 What’s Inside the Tutorial

- 🔢 Dimensionality reduction on `digits` dataset  
- 📊 Explained variance analysis  
- 📈 2D visualization of data clusters  
- 🔍 PCA + Logistic Regression classifier

📘 Notebook: [`pca_tutorial.ipynb`](./pca_tutorial.ipynb)

---

## 📂 File Structure

- `pca_tutorial.ipynb` – Full PCA tutorial notebook  
- `README.md` – This file  
- `references.md` – Suggested readings and tutorials

---

## 📚 Recommended Reading

- [scikit-learn: PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)  
- [Wikipedia: Principal Component Analysis](https://en.wikipedia.org/wiki/Principal_component_analysis)  
- [TDS: PCA Intuition and Implementation](https://towardsdatascience.com/a-step-by-step-explanation-of-principal-component-analysis-pca-6c5f7f7c99e0)

---

## 🚀 Try It Yourself

- Tune `n_components` manually or with explained variance  
- Combine with clustering or classification models  
- Apply to your own high-dimensional dataset  
- Visualize PCA components using `loadings` or `heatmaps`

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
