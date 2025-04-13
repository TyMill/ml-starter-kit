# Autoencoder (AE)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/autoencoder/autoencoder_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

An **Autoencoder (AE)** is an unsupervised neural network that learns a compressed (latent) representation of input data.  
It's trained to **reconstruct its own input**, making it powerful for dimensionality reduction, denoising, and anomaly detection.

---

## 🔍 What is an Autoencoder?

Autoencoders are composed of two main parts:

- **Encoder**: compresses the input to a latent space  
- **Decoder**: reconstructs the input from the latent representation  

The network is trained by minimizing reconstruction loss, usually Mean Squared Error (MSE).

---

## 🧠 When to Use

- Dimensionality reduction (nonlinear PCA alternative)
- Denoising and feature learning
- Pretraining for deep networks
- Anomaly detection
- Image or signal reconstruction

---

## ✅ Advantages

- Learns complex nonlinear embeddings
- Unsupervised learning – no labels required
- Flexible architecture (deep, convolutional, variational, etc.)
- Visualization and interpretation of latent features

## ❌ Disadvantages

- Requires careful tuning and architecture design
- May memorize input without generalizing
- Can be outperformed by simpler models if poorly regularized

---

## 🧪 What’s Inside the Tutorial

This notebook includes:
- 🧱 Fully connected autoencoder in Keras
- 🔍 Visualization of 2D latent space vs PCA
- 🧠 Digits dataset for reconstruction and evaluation
- 🚨 Anomaly detection via reconstruction error
- 📉 Loss curves and error distribution analysis

📘 Notebook: [`autoencoder_tutorial.ipynb`](./autoencoder_tutorial.ipynb)

---

## 📂 File Structure

- `autoencoder_tutorial.ipynb` – Full implementation and experiments
- `README.md` – This file
- `references.md` – External resources

---

## 📚 Recommended Reading

- [Keras Autoencoder Guide](https://keras.io/examples/autoencoder/)
- [Wikipedia: Autoencoder](https://en.wikipedia.org/wiki/Autoencoder)
- [scikit-learn: PCA (comparison)](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)

---

## ✨ Example Visualization

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Autoencoder_structure.png/512px-Autoencoder_structure.png" width="500"/>
</p>

---

## 🧠 Try It Yourself

- Try convolutional autoencoders on image data
- Replace activation functions (ReLU, tanh, leaky ReLU)
- Use `encoder.predict(X)` for compressed features
- Visualize anomaly scores in a business use case

---

Created with 🧬 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
