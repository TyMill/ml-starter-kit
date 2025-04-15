# Decision Trees

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/decision_tree/decision_tree_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Decision Trees** are intuitive and powerful models used for classification and regression.  
They mimic human decision-making with a flowchart-like structure, making them highly interpretable.

---

## 🌳 What is a Decision Tree?

- **Internal nodes**: decision rules on features  
- **Branches**: outcomes of the decision  
- **Leaves**: final predictions or class labels  

The model splits data recursively to reduce impurity (e.g., Gini or entropy).

---

## ✅ Advantages

- Easy to interpret and visualize  
- Handles both numerical and categorical data  
- Requires minimal preprocessing  
- Non-linear boundaries without transformations

## ❌ Disadvantages

- Can overfit (especially with deep trees)  
- Sensitive to small data changes  
- Greedy splitting doesn’t guarantee global optimum

---

## 🧪 What’s Inside the Tutorial

- 🌸 Classification on the Iris dataset  
- 🌳 Training a DecisionTreeClassifier (`sklearn`)  
- 📊 Visualizing the tree and extracting rules  
- 🧠 Evaluation with confusion matrix & classification report  
- 🔄 Cross-validation and effect of tree depth

📘 Notebook: [`decision_tree_tutorial.ipynb`](./decision_tree_tutorial.ipynb)

---

## 📂 File Structure

- `decision_tree_tutorial.ipynb` – Full decision tree pipeline  
- `README.md` – This file  
- `references.md` – Further resources

---

## 📚 Recommended Reading

- [scikit-learn: Decision Trees](https://scikit-learn.org/stable/modules/tree.html)  
- [Wikipedia: Decision Tree Learning](https://en.wikipedia.org/wiki/Decision_tree_learning)  
- [ML Cheatsheet – Decision Trees](https://ml-cheatsheet.readthedocs.io/en/latest/decision_trees.html)

---

## 🚀 Try It Yourself

- Tune `max_depth`, `min_samples_split`, `criterion`  
- Try `DecisionTreeRegressor` for regression tasks  
- Use `export_text()` to extract explainable rules  
- Compare with RandomForest or GradientBoosting

---

Created with 🌿 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
