# Sentiment Analysis Using IndoBERT

Binary sentiment analysis of Indonesian Twitter data using **IndoBERT**
to classify public opinion into **Positive** and **Negative** sentiment.

---

## 📌 Project Overview

This project is an undergraduate thesis focusing on **sentiment analysis
of Indonesian-language Twitter data** using **IndoBERT**, a pre-trained
language model specifically designed for Bahasa Indonesia.

The objective of this project is to build a robust **binary sentiment
classification pipeline** by combining data crawling, text preprocessing,
data augmentation, and fine-tuning IndoBERT on real-world social media data.

This repository showcases an **end-to-end NLP workflow**, from raw data
collection to model training and evaluation.

---

## 🎯 Objectives

- Collect Indonesian Twitter data related to political discourse
- Clean and normalize informal social media text
- Prepare labeled datasets for supervised learning
- Handle data imbalance using data augmentation
- Fine-tune IndoBERT for **binary sentiment classification**
- Evaluate model performance and analyze results

---

## 🧑‍💻 My Role

This project was completed as an **individual undergraduate thesis**.
All stages of the workflow—including data preparation, modeling, and
evaluation—were designed and implemented by me under academic supervision.

---

## 🧠 Methodology

### 1. Data Collection
- Crawling Indonesian Twitter data based on relevant keywords
- Filtering and organizing raw tweets for further processing

### 2. Text Preprocessing
- Case folding
- Noise removal (URLs, mentions, hashtags, emojis)
- Token normalization for informal Indonesian words
- Stopword removal

### 3. Data Labeling
- Manual and rule-based sentiment labeling
- **Binary sentiment classes:**
  - **Positive**
  - **Negative**

### 4. Data Augmentation
- Applied augmentation techniques to address class imbalance
- Augmentation logic is documented in the notebooks

> **Note:** The augmented dataset is not stored in this repository.
> The augmentation process can be reproduced by rerunning the notebook.

### 5. Model Training (IndoBERT)
- Fine-tuning **IndoBERT Base**
- Tokenization using IndoBERT tokenizer
- Supervised training with binary sentiment labels

### 6. Evaluation
- Accuracy
- Precision, Recall, and F1-score
- Confusion matrix analysis for binary classification

---

## 🧪 Model Used

- **IndoBERT (Indonesian BERT)**
  - Pre-trained language model optimized for Bahasa Indonesia
  - Well-suited for binary sentiment classification tasks

---

## 📊 Key Results
- IndoBERT achieved strong performance for binary sentiment classification
- Data augmentation improved model robustness on imbalanced data
- The model successfully captured contextual sentiment in Indonesian tweets

---

## 🛠️ Tools & Technologies
Python, pandas, PyTorch, Hugging Face Transformers, IndoBERT, scikit-learn, Google Colab
