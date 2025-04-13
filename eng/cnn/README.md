# Convolutional Neural Network (CNN)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/cnn/cnn_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

A **Convolutional Neural Network (CNN)** is a deep learning model specifically designed for image data.  
CNNs automatically learn spatial hierarchies of features through convolutional layers, making them highly effective for visual recognition tasks.

---

## 🔍 What is a CNN?

CNNs consist of several key components:

- 🧱 **Convolutional Layers** – learn spatial features using kernels/filters  
- 📉 **Pooling Layers** – downsample feature maps (e.g., MaxPooling)  
- 🔁 **Activation Functions** – introduce non-linearity (ReLU, LeakyReLU)  
- 🧠 **Fully Connected Layers** – final classification steps (Dense)

Trained end-to-end using **backpropagation**, CNNs learn directly from raw pixels.

---

## 🧠 When to Use

- Image classification (e.g., MNIST, CIFAR, Fashion MNIST)  
- Object detection and segmentation  
- Facial recognition, OCR, medical imaging  
- Any data with **spatial structure**

---

## ✅ Advantages

- Learns relevant features automatically (no manual feature engineering)  
- Handles **translation invariance** and spatial locality  
- Reduces parameter count vs fully connected networks  
- Scales well with large image datasets

## ❌ Disadvantages

- Requires more compute than traditional ML models  
- Needs more data for effective generalization  
- Interpretation can be complex (black box effect)

---

## 🧪 What’s Inside the Tutorial

This notebook includes:
- 🧠 A custom CNN built in Keras for **Fashion MNIST** classification  
- 🧱 Architecture: Conv2D → MaxPooling → Dense  
- 📈 Visualization of training history (accuracy/loss)  
- 📊 Detailed evaluation with `classification_report`  
- 🖼️ Visualization of predictions with true vs predicted labels

📘 Notebook: [`cnn_tutorial.ipynb`](./cnn_tutorial.ipynb)

---

## 📂 File Structure

- `cnn_tutorial.ipynb` – Main tutorial notebook  
- `README.md` – This file  
- `references.md` – Hand-picked learning resources

---

## 📚 Recommended Reading

- [Keras: CNN Example – MNIST ConvNet](https://keras.io/examples/vision/mnist_convnet/)
- [TensorFlow: CNN Tutorial](https://www.tensorflow.org/tutorials/images/cnn)
- [Wikipedia: Convolutional Neural Network](https://en.wikipedia.org/wiki/Convolutional_neural_network)

---

## 🧠 CNN Architecture (Example)

```text
Input: (28x28x1 grayscale image)
↓ Conv2D (32 filters, 3x3) + ReLU
↓ MaxPooling2D (2x2)
↓ Conv2D (64 filters, 3x3) + ReLU
↓ MaxPooling2D (2x2)
↓ Flatten
↓ Dense(64) + ReLU
↓ Dense(10) + Softmax (for classification)
'''
---

##🧠 Try It Yourself

```text
↓ Add Dropout() for regularization
↓ Replace ReLU with LeakyReLU()
↓ Try deeper networks (ResNet, VGG)
↓ Apply to your own image datasets
↓ Visualize feature maps from intermediate layers

---

Created with 🧬 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)

