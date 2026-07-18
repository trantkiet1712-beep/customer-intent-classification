<div align="center">

# 🇻🇳 Vietnamese Customer Intent Classification

### Customer Intent Recognition using PhoBERT & Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red?logo=pytorch)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

*A Natural Language Processing project for Vietnamese E-commerce Customer Intent Classification.*

</div>

---

# 📌 Overview

This project aims to classify Vietnamese customer intents from e-commerce conversations using both traditional Machine Learning algorithms and the PhoBERT Transformer model.

The project compares different approaches to determine the most effective model for Vietnamese intent classification.

---

# 🎯 Objectives

- Build an Intent Classification system for Vietnamese language.
- Compare traditional Machine Learning models with Transformer-based models.
- Fine-tune PhoBERT for Vietnamese NLP.
- Evaluate model performance using standard classification metrics.

---

# 🛠 Technologies

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| NLP | PhoBERT, HuggingFace Transformers |
| Machine Learning | Scikit-Learn |
| Data Processing | Pandas, NumPy |
| Deep Learning | PyTorch |
| Visualization | Matplotlib |

---

# 📂 Project Structure

```text
customer-intent-classification/
│
├── data/
│   ├── data_cleaned.csv
│   └── data_augmented.csv
│
├── notebooks/
│   ├── XuLyData.ipynb
│   ├── AugmentData.ipynb
│   └── BaoCao_final.ipynb
│
├── report/
│   └── BaoCao.pdf
│
└── README.md
```

---

# 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Data Augmentation
      │
      ▼
Train/Test Split
      │
      ▼
Feature Extraction
      │
      ├─────────────► TF-IDF
      │
      ▼
Traditional ML Models
      │
      ├── Naive Bayes
      ├── Logistic Regression
      └── Linear SVM
      │
      ▼
PhoBERT Fine-tuning
      │
      ▼
Evaluation
      │
      ▼
Accuracy • Precision • Recall • F1-score
```

---

# 🤖 Models

- Naive Bayes
- Logistic Regression
- Linear SVM
- PhoBERT (Transformer)

---

# 📊 Performance Comparison

| Model | Accuracy |
|--------|----------|
| Naive Bayes | 84.79% |
| Logistic Regression | 91.03% |
| Linear SVM | 93.19% |
| **PhoBERT** | **95.06%** ✅ |

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

# 💡 Key Features

✅ Vietnamese NLP

✅ Intent Classification

✅ PhoBERT Fine-tuning

✅ Machine Learning Comparison

✅ HuggingFace Transformers

---

# 🚀 Future Improvements

- Deploy as REST API using FastAPI
- Build a Streamlit Web Application
- Collect larger Vietnamese datasets
- Hyperparameter Optimization
- Deploy on Hugging Face Spaces

---

# 📄 Report

The complete academic report is available in:

```
report/BaoCao.pdf
```

---

# 👨‍💻 Author

**Tran Tuan Kiet**

Student | Ho Chi Minh City University of Industry and Trade (HUIT)

GitHub:

https://github.com/trantkiet1712-beep

---

# ⭐ If you find this project useful, please give it a star!
