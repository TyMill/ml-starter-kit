# Naive Bayes

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/naive_bayes/naive_bayes_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Naive Bayes** is a family of simple yet powerful probabilistic classifiers based on Bayes' theorem and the strong assumption of feature independence.

---

## 🔍 What is Naive Bayes?

Naive Bayes calculates the probability of a class given input features using Bayes' theorem:

$$
P(y | x_1, ..., x_n) = \\frac{P(y) \\prod_{i=1}^{n} P(x_i | y)}{P(x_1, ..., x_n)}
$$

### Main Variants:
- **GaussianNB** – Assumes normal distribution for numeric features
- **MultinomialNB** – Ideal for word counts and discrete features (e.g. text classification)
- **BernoulliNB** – Binary/boolean features (e.g. spam filters)

---

## 🧠 When to Use

- Text classification: spam detection, topic classification
- High-dimensional data
- When features are (somewhat) independent
- Fast inference in large-scale systems

---

## ✅ Advantages

- Simple, fast, and interpretable
- Requires less training data
- Performs well with high-dimensional input
- Probabilistic output

## ❌ Disadvantages

- Assumes independence between features (rare in practice)
- Not great for highly correlated or complex feature spaces
- Lower performance on non-text data compared to other models

---

## 🧪 What’s Inside the Tutorial

This notebook includes:
- 📊 GaussianNB on synthetic data with evaluation
- 🎯 2D decision boundary visualization
- 📝 MultinomialNB on real-world text (20 Newsgroups)
- ⚖️ Comparison with Logistic Regression
- 📈 Evaluation using `classification_report`, accuracy, confusion matrix

📘 Notebook: [`naive_bayes_tutorial.ipynb`](./naive_bayes_tutorial.ipynb)

---

## 📂 File Structure

- `naive_bayes_tutorial.ipynb` – Full implementation and comparison
- `README.md` – This document
- `references.md` – External resources and reading list

---

## 📚 Recommended Reading

- [scikit-learn: Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [Wikipedia: Naive Bayes classifier](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
- [StatQuest Video: Naive Bayes](https://www.youtube.com/watch?v=O2L2Uv9pdDA)

---

## ✨ Example Visualization

![Bayes](https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/Bayes_rule_diagram.svg/512px-Bayes_rule_diagram.svg.png)

---

## 🧠 Try It Yourself

- Use different feature extractors (CountVectorizer, TfidfVectorizer)
- Test with sentiment datasets (IMDB, Yelp)
- Compare performance on multiclass datasets
- Try using BernoulliNB with binary text inputs

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
