# BERT Fine-Tuning for Sentiment Analysis

This project demonstrates fine-tuning of a pre-trained BERT model on the IMDB Movie Reviews dataset for binary sentiment classification.

---

## Objective

To build and evaluate a transformer-based text classification model using BERT and compare different fine-tuning strategies.

---

## Dataset

- **Dataset:** IMDB Movie Reviews Dataset
- **Source:** [Kaggle - IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Total Samples:** 50,000
- **Balanced Classes:** Yes
- **Task:** Binary Sentiment Classification (Positive / Negative)

---

## Workflow

1. Data Preprocessing
2. Train / Validation / Test Split
3. Tokenization using `bert-base-uncased`
4. Fine-Tuning BERT Model
5. Model Evaluation
6. Experiments with Different Fine-Tuning Strategies

---

## Experiments Performed

- **Full Fine-Tuning**
- **Frozen BERT Layers**
- **Fine-Tuning Last 2 Layers**

---

## Key Insights

- Full fine-tuning achieved the best performance.
- Freezing all BERT layers significantly reduced performance.
- Fine-tuning only the last two layers provided a strong balance between accuracy and efficiency.

---

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Kaggle Notebooks