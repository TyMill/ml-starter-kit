# Recurrent Neural Networks (RNN)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/rnn/rnn_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Recurrent Neural Networks (RNNs)** are designed to process sequential data by maintaining internal memory across steps.  
They are fundamental tools in time series forecasting, language modeling, and sequence classification.

---

## 🔍 What is an RNN?

- A type of neural network with **recurrent connections**  
- Captures dependencies in **sequential or time-series data**  
- Maintains a hidden state across time steps  
- Often used as the basis for LSTM and GRU networks

---

## ✅ Advantages

- Captures temporal patterns and sequence order  
- Flexible input and output dimensions  
- Good for modeling dynamic behavior and feedback loops

## ❌ Disadvantages

- Prone to vanishing gradients  
- Struggles with long-term dependencies  
- Slower training compared to feedforward models

---

## 🧪 What’s Inside the Tutorial

- 🌀 Sine wave prediction using RNN in PyTorch  
- 📊 Sequence slicing and batch training  
- ⚙️ Manual forward loop over time  
- 📈 Forecast visualization and loss analysis

📘 Notebook: [`rnn_tutorial.ipynb`](./rnn_tutorial.ipynb)

---

## 📂 File Structure

- `rnn_tutorial.ipynb` – Full PyTorch-based tutorial  
- `README.md` – This file  
- `references.md` – Additional learning resources

---

## 📚 Recommended Reading

- [PyTorch: RNN Module](https://pytorch.org/docs/stable/generated/torch.nn.RNN.html)  
- [Wikipedia: Recurrent Neural Networks](https://en.wikipedia.org/wiki/Recurrent_neural_network)  
- [TDS: RNNs Explained](https://towardsdatascience.com/understanding-rnns-and-lstms-f7cdf6dfc14e)

---

## 🚀 Try It Yourself

- Replace `RNN` with `LSTM` or `GRU`  
- Use multivariate time series inputs  
- Tune `hidden_size`, `num_layers`, and sequence length  
- Train on real-world data (e.g. stock prices, weather)

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
