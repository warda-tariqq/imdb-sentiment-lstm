# 🎬 IMDB Sentiment Classification using LSTM

This project is part of the **Fellowship.AI Cohort 35 NLP Challenge**. It uses a deep learning approach (LSTM) to classify IMDB movie reviews as **positive** or **negative**.

## 📌 Problem Statement
Given 50,000 labeled IMDB reviews, the goal is to predict whether a movie review expresses positive or negative sentiment using Natural Language Processing and deep learning techniques.

---

## 📂 Dataset

- Source: [Kaggle - IMDB Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Total: 50,000 reviews (25K for training, 25K for testing)
- Binary classification: `positive` or `negative`

---

## 🛠️ Preprocessing Steps

- HTML and punctuation removal
- Lowercasing and stopword removal
- Tokenization and sequence padding

---

## 🧠 Model Architecture

- `Embedding` layer: 10,000-word vocab, 64-dim vector
- `LSTM` layer: 64 units
- `Dropout`: 0.5
- `Dense`: ReLU → Sigmoid
- Loss: Binary Crossentropy  
- Optimizer: Adam with gradient clipping

---

## 📈 Results

| Metric        | Score     |
|---------------|-----------|
| **Accuracy**  | 88%       |
| **Precision** | 86–90%    |
| **Recall**    | 86–90%    |
| **F1-Score**  | 0.88      |


