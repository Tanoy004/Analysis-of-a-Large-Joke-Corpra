# Analysis of a Large Joke Corpus (NLP)

This repository contains a data science and NLP-based study on humor classification using large-scale joke datasets, with a focus on improving detection of offensive (NSFW) content through data augmentation techniques.

---

## 📌 Overview

Humor detection is a challenging problem due to cultural and contextual variations. This project explores the classification of jokes into Safe for Work (SFW) and Not Safe for Work (NSFW) categories using machine learning and transformer-based models.

A key contribution of this work is the use of **GPT-generated synthetic data** to augment training datasets and improve classification performance.

---

## 🧠 Methodology

- Dataset: Reddit joke corpus (~1M jokes)
- Data augmentation:
  - Generated SFW counterparts for NSFW jokes using GPT
- Models used:
  - DistilBERT
  - RoBERTa
  - Traditional ML baselines (e.g., SVM)
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score

---

## 📊 Key Findings

- DistilBERT achieved:
  - **83.08% accuracy**
  - **82.93% F1-score**
- RoBERTa improved recall by **+4.04%**
- GPT-augmented datasets significantly improved classification performance
- Combining human-written and synthetic data led to better generalization

---

## 📁 Repository Contents

- `ProjectDataSetup.ipynb` – Data preprocessing and setup  
- `Jokes-GPT-Augmented.csv` – Augmented dataset  
- `Jokes-GPT-Only.csv` – Synthetic dataset  
- `JOKES-wo-GPT.csv` – Original dataset  
- `Final Report` – Detailed analysis and results  

---

## ⚙️ Implementation

- Language: Python  
- Libraries:  
  - HuggingFace Transformers  
  - Scikit-learn  
  - Pandas / NumPy  

---

## 👨‍💻 Role

Primary contributor. Designed the data analysis pipeline, implemented NLP models, performed experiments, and analyzed the impact of GPT-based data augmentation on humor classification.

---

## 🎓 Academic Context

This project was completed as part of graduate-level coursework in Data Science and reflects applied research in NLP and machine learning.

---

## 🚀 Applications

- Content moderation systems  
- Offensive language detection  
- AI safety and filtering  
- Conversational AI systems  

---

## 📌 Note

This repository represents an academic project and is intended for research and educational purposes.

---
