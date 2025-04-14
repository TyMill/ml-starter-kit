# DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/dbscan/dbscan_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**DBSCAN** is a powerful unsupervised clustering algorithm that groups together points in high-density regions and marks others as outliers.

It is especially useful when:
- The number of clusters is unknown
- Clusters have irregular shapes
- The data contains noise

---

## 🔍 How DBSCAN Works

- **Core Points**: Have at least `min_samples` neighbors within `eps` radius  
- **Border Points**: Close to a core point, but with fewer neighbors  
- **Noise Points**: Not part of any cluster

---

## ✅ Advantages

- Does **not require** the number of clusters  
- Can find **arbitrary-shaped clusters**  
- Robust to **outliers and noise**

## ❌ Disadvantages

- Sensitive to `eps` and `min_samples`  
- Struggles in high-dimensional spaces  
- Performance drops on non-uniform densities

---

## 🧪 What’s Inside the Tutorial

- 📊 Clustering on moon-shaped data
- 🤖 Comparison with KMeans on blobs
- 📈 Silhouette score evaluation
- 🔍 Tuning `eps` and visualizing the results

📘 Notebook: [`dbscan_tutorial.ipynb`](./dbscan_tutorial.ipynb)

---

## 📂 File Structure

- `dbscan_tutorial.ipynb` – Full DBSCAN tutorial  
- `README.md` – This file  
- `references.md` – Further reading

---

## 📚 Recommended Reading

- [scikit-learn: DBSCAN](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)  
- [Wikipedia: DBSCAN](https://en.wikipedia.org/wiki/DBSCAN)  
- [Density-based clustering concepts](https://cs.dbvis.de/teaching/ws1718/dbscan/)

---

## 🚀 Try It Yourself

- Change distance metric to `'manhattan'`, `'cosine'`, etc.  
- Apply to geospatial or social network datasets  
- Use DBSCAN as preprocessing for noise removal  
- Plot clusters using UMAP or t-SNE projections

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
