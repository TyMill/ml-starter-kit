# Support Vector Machines (SVM)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/svm/svm_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Support Vector Machines (SVM)** are powerful supervised learning algorithms used for classification and regression.  
They aim to find the hyperplane that best separates classes in feature space with the maximum margin.

---

## 🔍 What is an SVM?

- Maximizes the **margin** between classes  
- Uses **support vectors** to define the decision boundary  
- Can apply **kernel tricks** to handle non-linear data:
  - Linear
  - Polynomial
  - RBF (Gaussian)

---

## ✅ Advantages

- Effective in high-dimensional spaces  
- Memory-efficient (only uses support vectors)  
- Versatile with different kernel functions

## ❌ Disadvantages

- Less effective on large datasets  
- Sensitive to outliers  
- Requires careful tuning of `C` and `gamma`

---

## 🧪 What’s Inside the Tutorial

- 🏥 Classification on the Breast Cancer dataset  
- 🔧 Model training and hyperparameter tuning with GridSearchCV  
- 📊 Accuracy, confusion matrix, and classification report  
- 🎛 Kernel selection and tuning

📘 Notebook: [`svm_tutorial.ipynb`](./svm_tutorial.ipynb)

---

## 📂 File Structure

- `svm_tutorial.ipynb` – Full SVM tutorial notebook  
- `README.md` – This file  
- `references.md` – Additional resources

---

## 📚 Recommended Reading

- [scikit-learn: SVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)  
- [Wikipedia: Support Vector Machine](https://en.wikipedia.org/wiki/Support_vector_machine)  
- [TDS: Understanding SVMs](https://towardsdatascience.com/understanding-support-vector-machine-example-code-in-python-7fbcffc9d7c0)

---

## 🚀 Try It Yourself

- Use `poly` and `rbf` kernels  
- Try `SVC(probability=True)` for probabilistic output  
- Tune `C`, `gamma`, and kernel with cross-validation  
- Visualize decision boundaries for 2D data

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
