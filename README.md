# 🧠 Overview

As generative AI tools become ubiquitous in content creation, distinguishing between **AI-generated** and **human-written** content is critical for transparency, trust, and digital ethics.  
This project provides a hands-on, modular framework for assigning attribution labels to text using lightweight, open-source methods.

---

## 🔍 What You'll Learn

- How to label content as **"AI-Generated"**, **"Human-Written"**, or **"Human–AI Co-Creation"**
- How to set up attribution workflows in **Google Colab** using Python and open-source NLP tools
- How to apply three distinct attribution methods:

---

## ⚙️ Methods Included

### 1. 💡 Heuristic Scoring

Rule-based comparisons using:

- **Levenshtein Distance** – for edit detection  
- **Cosine Similarity** – on transformer-based embeddings

> 🛠 Useful for simple attribution and edit tracking with minimal setup.

---

### 2. 📊 Lightweight Classifier

A trainable AI detector using:

- **Sentence Transformers** – to extract embeddings  
- **Logistic Regression** – to classify content origin

> ✅ Suited for controlled environments with labeled training data.

---

### 3. 🎯 Zero-Shot Classification

Use pretrained NLI models like:

- `BART-MNLI`  
- `XLM-RoBERTa-XNLI`

> ⚡️ No fine-tuning needed. Just input candidate labels and let the model decide!

---

## 🧰 Installation

Install required packages:

```bash
pip install textdistance transformers sentence-transformers scikit-learn

!pip install textdistance transformers sentence-transformers scikit-learn

