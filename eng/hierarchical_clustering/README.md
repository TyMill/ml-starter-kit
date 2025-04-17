# Hierarchical Clustering

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/hierarchical_clustering/hierarchical_clustering_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Hierarchical Clustering** is an unsupervised machine learning technique that creates a hierarchy of clusters.  
It doesn't require specifying the number of clusters in advance and produces a dendrogram that shows how clusters are merged step-by-step.

---

## 🔍 What is Hierarchical Clustering?

- A **tree-based** method of clustering  
- Builds clusters recursively by merging or splitting  
- Two main strategies:
  - **Agglomerative** (bottom-up): Start with individual points
  - **Divisive** (top-down): Start with one big cluster

Linkage methods include:
- **Ward’s method**
- **Complete linkage**
- **Average linkage**
- **Single linkage**

---

## ✅ Advantages

- Does not require number of clusters  
- Dendrogram provides insight into data structure  
- Works with different linkage criteria  
- Handles non-globular cluster shapes

## ❌ Disadvantages

- Not scalable for large datasets  
- Sensitive to noise and outliers  
- Results depend on chosen distance/linkage method

---

## 🧪 What’s Inside the Tutorial

- 🎯 Clustering synthetic 2D data  
- 🌿 Building and plotting dendrograms  
- 🧠 Visual comparison of linkage methods  
- 📊 Assigning clusters with `fcluster`

📘 Notebook: [`hierarchical_clustering_tutorial.ipynb`](./hierarchical_clustering_tutorial.ipynb)

---

## 📂 File Structure

- `hierarchical_clustering_tutorial.ipynb` – Main tutorial notebook  
- `README.md` – This file  
- `references.md` – Further reading

---

## 📚 Recommended Reading

- [scikit-learn: Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)  
- [SciPy: Hierarchical Clustering](https://docs.scipy.org/doc/scipy/reference/cluster.hierarchy.html)  
- [Wikipedia: Hierarchical Clustering](https://en.wikipedia.org/wiki/Hierarchical_clustering)

---

## 🚀 Try It Yourself

- Change linkage method (e.g., `average`, `single`)  
- Use real-world datasets (e.g., gene expression, customer segmentation)  
- Visualize with `seaborn.clustermap`  
- Combine with PCA for high-dimensional data

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
