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

The architecture is end-to-end differentiable and trained using backpropagation.

---

## 🧠 When to Use

- Image classification (MNIST, CIFAR, Fashion MNIST)  
- Object detection & segmentation  
- Document or character recognition  
- Any data with **spatial structure**

---

## ✅ Advantages

- Learns relevant features automatically  
- Handles translation invariance and spatial locality  
- Reduces parameter count vs fully connected networks  
- Scales well with large image datasets

## ❌ Disadvantages

- Requires more compute than traditional models  
- Needs more data for effective generalization  
- Interpretation can be complex

---

## 🧪 What’s Inside the Tutorial

This notebook includes:
- 🧠 Custom CNN for Fashion MNIST classification
- 🧱 Conv2D → MaxPooling → Dense architecture
- 📈 Training/validation accuracy and loss plots
- 📊 Evaluation with `classification_report`
- 🖼️ Predictions visualization

📘 Notebook: [`cnn_tutorial.ipynb`](./cnn_tutorial.ipynb)

---

## 📂 File Structure

- `cnn_tutorial.ipynb` – Full implementation and experiments  
- `README.md` – This file  
- `references.md` – External resources

---

## 📚 Recommended Reading

- [Keras: CNN Guide](https://keras.io/examples/vision/mnist_convnet/)
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
```

---

## 🚀 Try It Yourself

```text
↓ Add Dropout() for regularization
↓ Replace ReLU with LeakyReLU()
↓ Try deeper networks (ResNet, VGG)
↓ Apply to your own image datasets
↓ Visualize feature maps from intermediate layers
```

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
