# Transformers

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TyMill/ml-starter-kit/blob/main/eng/transformer/transformer_tutorial.ipynb)
[![Try on Kaggle](https://img.shields.io/badge/Open%20in-Kaggle-blue)](https://www.kaggle.com/code)
[![JupyterLite](https://img.shields.io/badge/Try%20it-JupyterLite-orange)](https://jupyterlite.github.io/demo)

**Transformers** are cutting-edge deep learning models based on self-attention mechanisms.  
They have revolutionized natural language processing (NLP) and are the backbone of models like BERT, GPT, T5, and more.

---

## 🔍 What is a Transformer?

- Uses **self-attention** instead of recurrence to model sequence relationships  
- Can **process input in parallel**, making training faster  
- Learns **contextual representations** of words and sentences  
- Foundation for modern NLP and vision models

---

## ✅ Advantages

- Highly parallelizable  
- Effective for long-range dependencies  
- Works well for both text and vision tasks  
- Enables pretraining on massive datasets

## ❌ Disadvantages

- Requires large amounts of data and compute  
- Can be harder to interpret  
- Pretrained models may have biases

---

## 🧪 What’s Inside the Tutorial

- 📚 Load a text dataset (`AG News`)  
- 🧠 Tokenize using `BertTokenizer`  
- 🔍 Extract contextual embeddings using `BertModel`  
- 📊 Visualize the `CLS` token embedding from the transformer output

📘 Notebook: [`transformer_tutorial.ipynb`](./transformer_tutorial.ipynb)

---

## 📂 File Structure

- `transformer_tutorial.ipynb` – HuggingFace-based tutorial  
- `README.md` – This file  
- `references.md` – Learning resources and official docs

---

## 📚 Recommended Reading

- [Hugging Face Transformers Docs](https://huggingface.co/docs/transformers/index)  
- [Illustrated Transformer (Jay Alammar)](https://jalammar.github.io/illustrated-transformer/)  
- [Wikipedia: Transformer (Machine Learning)](https://en.wikipedia.org/wiki/Transformer_(machine_learning_model))

---

## 🚀 Try It Yourself

- Replace `BertModel` with `DistilBERT`, `RoBERTa`, or `GPT2`  
- Use outputs for classification, clustering, or sentiment analysis  
- Tokenize longer documents with truncation or sliding window  
- Use `Trainer` from HuggingFace to fine-tune models

---

Created with 🧠 by **Tymoteusz Miller** — part of the [ML Starter Kit](https://github.com/TyMill/ml-starter-kit)
