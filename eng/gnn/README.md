# Graph Neural Networks (GNN)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/gnn/gnn_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Graph Neural Networks (GNNs)** are powerful models for learning on graph-structured data.  
They are widely used in recommendation systems, social networks, biological networks, and fraud detection.

---

## 🔍 What is a GNN?

GNNs operate on nodes and edges. They learn **node representations** by aggregating features from neighbors.

Typical GNN layers include:
- **GCNConv** – Graph Convolution
- **GATConv** – Graph Attention
- **GraphSAGE** – Aggregated sampling

---

## ✅ Advantages

- Captures graph structure and relationships  
- Learns from node features and neighborhoods  
- Scalable to large graphs with sparse matrices  
- Works with transductive and inductive settings

## ❌ Disadvantages

- Requires specialized libraries (e.g. `torch-geometric`)  
- Complex training dynamics  
- Visualization and debugging can be harder

---

## 🧪 What’s Inside the Tutorial

- 🗂️ Node classification on **Cora** citation dataset  
- ⚙️ PyTorch Geometric setup and GCN model  
- 🔁 2-layer GCN training loop with dropout  
- 📈 Test accuracy reporting and logging

📘 Notebook: [`gnn_tutorial.ipynb`](./gnn_tutorial.ipynb)

---

## 📂 File Structure

- `gnn_tutorial.ipynb` – Full implementation of a GCN model  
- `README.md` – This file  
- `references.md` – Extra learning resources

---

## 📚 Recommended Reading

- [PyG: PyTorch Geometric Documentation](https://pytorch-geometric.readthedocs.io/en/latest/)
- [Stanford CS224W: Machine Learning with Graphs](http://web.stanford.edu/class/cs224w/)
- [Wikipedia: Graph Neural Networks](https://en.wikipedia.org/wiki/Graph_neural_network)

---

## 🚀 Try It Yourself

- Swap `GCNConv` for `GATConv` or `GINConv`  
- Use your own graph datasets (e.g., social or molecular)  
- Visualize embeddings using t-SNE  
- Try edge-level or graph-level tasks

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
