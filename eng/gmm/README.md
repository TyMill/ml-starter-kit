# Gaussian Mixture Models (GMM)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/gmm/gmm_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Gaussian Mixture Models (GMMs)** are probabilistic models that assume the data is generated from a mixture of several Gaussian distributions.  
They are commonly used for clustering, density estimation, and anomaly detection.

---

## 🔍 What is a GMM?

GMM models the probability distribution of a dataset as a weighted sum of Gaussian components.

- **Soft clustering** – Each point has a probability of belonging to each cluster  
- **Maximum likelihood** – Parameters are optimized via the EM algorithm  
- **Model selection** – Use AIC/BIC to determine the number of components

---

## ✅ Advantages

- Flexible cluster shapes  
- Soft assignments (probabilistic)  
- Applicable to both clustering and density estimation  
- Can model overlapping clusters

## ❌ Disadvantages

- Assumes Gaussian distribution  
- Sensitive to initialization  
- May converge to local minima

---

## 🧪 What’s Inside the Tutorial

- 🎯 Fit GMM to synthetic data  
- 🔁 Compare GMM and KMeans  
- 📊 Evaluate using Silhouette Score, AIC, BIC  
- 🔵 Visualize 2D Gaussian ellipses

📘 Notebook: [`gmm_tutorial.ipynb`](./gmm_tutorial.ipynb)

---

## 📂 File Structure

- `gmm_tutorial.ipynb` – Full GMM tutorial  
- `README.md` – This file  
- `references.md` – Further reading

---

## 📚 Recommended Reading

- [scikit-learn: GaussianMixture](https://scikit-learn.org/stable/modules/generated/sklearn.mixture.GaussianMixture.html)  
- [Wikipedia: Gaussian Mixture Model](https://en.wikipedia.org/wiki/Mixture_model)  
- [Understanding GMMs (TDS)](https://towardsdatascience.com/gaussian-mixture-models-explained-6986c5a95c6e)

---

## 🚀 Try It Yourself

- Use `BayesianGaussianMixture` for automatic component selection  
- Combine GMM with PCA  
- Apply to anomaly detection tasks  
- Try on multivariate real-world data

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
