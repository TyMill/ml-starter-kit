# KMeans Clustering

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/kmeans/kmeans_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**KMeans Clustering** is one of the simplest and most popular unsupervised machine learning algorithms.  
It groups data points into `k` clusters by minimizing intra-cluster variance.

---

## 🔍 What is KMeans?

- Partitions data into **k clusters**  
- Minimizes the **sum of squared distances** between points and their assigned cluster centroids  
- Iterative algorithm:
  - Assign each point to the nearest centroid
  - Recompute centroids
  - Repeat until convergence

---

## ✅ Advantages

- Simple and fast  
- Easy to interpret  
- Scales well to large datasets  
- Effective on spherical clusters

## ❌ Disadvantages

- Requires setting `k`  
- Sensitive to outliers and initialization  
- Assumes clusters of similar size and density

---

## 🧪 What’s Inside the Tutorial

- 🔧 Fit KMeans to synthetic data  
- 📈 Visualize clusters and centroids  
- 🧠 Evaluate with `inertia` and `silhouette_score`  
- 📊 Use the Elbow Method to find optimal `k`

📘 Notebook: [`kmeans_tutorial.ipynb`](./kmeans_tutorial.ipynb)

---

## 📂 File Structure

- `kmeans_tutorial.ipynb` – Main tutorial notebook  
- `README.md` – This file  
- `references.md` – Further reading and videos

---

## 📚 Recommended Reading

- [scikit-learn: KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)  
- [Wikipedia: K-means clustering](https://en.wikipedia.org/wiki/K-means_clustering)  
- [TDS: KMeans Explained](https://towardsdatascience.com/k-means-clustering-algorithm-applications-evaluation-methods-and-drawbacks-aa03e644b48a)

---

## 🚀 Try It Yourself

- Compare KMeans with DBSCAN or GMM  
- Try different values of `k` and random seeds  
- Apply PCA before clustering  
- Use KMeans for color quantization in images

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
