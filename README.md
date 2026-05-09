# Comparison Between Traditional NLP and Transformer-Based Sentiment Analysis

This project performs sentiment analysis on IMDb movie reviews using two different approaches:

1. Traditional NLP Pipeline
2. Transformer-Based Pipeline

The goal is to classify movie reviews as:
- Positive
- Negative

---

# Dataset

The project uses the IMDb Dataset of 50K Movie Reviews.

Dataset source:
- IMDb Movie Reviews Dataset

---

# Project Objectives

The project compares:
- Traditional Natural Language Processing techniques
- Transformer-based deep learning models

The comparison focuses on:
- Accuracy
- Speed
- Context understanding
- Handling nuanced language

---

# Traditional NLP Pipeline

The traditional NLP workflow includes:

## Text Preprocessing
- Lowercasing
- Removing punctuation
- Tokenization
- Stop-word removal

## Feature Extraction
- TF-IDF Vectorization

## Machine Learning Model
- Logistic Regression

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

# Transformer-Based Pipeline

The transformer workflow uses:
- DistilBERT pretrained transformer model
- Hugging Face Transformers library

## Steps
- Transformer tokenization
- Sentiment classification using pretrained model
- Performance evaluation

---

# Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- Transformers
- Hugging Face
- Matplotlib
- Seaborn

---

# Results

| Model | Accuracy |
|---|---|
| Traditional NLP + Logistic Regression | 88.88% |
| Transformer Model | 89.80% |

---

# Comparison Summary

| Feature | Traditional NLP | Transformer Model |
|---|---|---|
| Feature Extraction | TF-IDF | Transformer Embeddings |
| Speed | Faster | Slower |
| Context Understanding | Limited | Better |
| Computational Cost | Low | Higher |

---

# Conclusion

The transformer-based model achieved slightly better accuracy due to its ability to understand contextual relationships between words. However, the traditional NLP model remained efficient, faster, and computationally simpler.

This project demonstrates the strengths and trade-offs between classical NLP approaches and modern transformer-based models for sentiment analysis tasks.

---

# Repository Structure

```text
├── Sentiment_Analysis.ipynb
├── README.md
├── requirements.txt
