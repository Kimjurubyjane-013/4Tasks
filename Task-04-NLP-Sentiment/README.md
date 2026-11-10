# Customer Review Sentiment Classification using TF-IDF

## Project Overview

This project develops an NLP-based sentiment classification system that analyzes customer reviews and predicts whether the sentiment is Positive or Negative.

## Objectives

- Clean and preprocess raw customer review text.
- Convert text into numerical features using TF-IDF.
- Train Multinomial Naive Bayes and Logistic Regression classifiers.
- Compare model performance using evaluation metrics.
- Implement a live sentiment prediction function.

## Dataset

**File:** `sentiment_reviews.csv`

Columns:
- `review_id`: Unique review identifier
- `review_text`: Customer review
- `sentiment`: Sentiment label

The original dataset contains positive, negative, and neutral labels. Neutral samples are excluded for binary classification.

## Technologies Used

- Python
- Pandas and NumPy
- NLTK
- Scikit-learn
- Matplotlib and Seaborn
- Joblib

## Methodology

1. Data Cleaning and Exploratory Data Analysis
2. Text Preprocessing and Lemmatization
3. TF-IDF Feature Extraction
4. Multinomial Naive Bayes Training
5. Logistic Regression Training
6. Model Evaluation and Comparison
7. Live Sentiment Prediction
8. Model Serialization

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

## Project Structure

```text
Task-04-NLP-Sentiment/
├── data/
│   └── sentiment_reviews.csv
├── notebooks/
│   └── sentiment_classification.ipynb
├── results/
│   ├── best_sentiment_model.pkl
│   ├── tfidf_vectorizer.pkl
│   ├── sentiment_pipeline.pkl
│   └── model_comparison.csv
├── README.md
└── requirements.txt
```

## Installation

```bash
python -m pip install -r requirements.txt
```

Download the required NLTK resources before running the notebook:

```python
import nltk

nltk.download("stopwords")
nltk.download("wordnet")
nltk.download("omw-1.4")
nltk.download("punkt")
nltk.download("punkt_tab")
```

## How to Run

1. Open the project folder.
2. Launch Jupyter Notebook.
3. Open `notebooks/sentiment_classification.ipynb`.
4. Run all cells sequentially.
5. Test custom customer reviews using `predict_sentiment()`.

## Model Results

See `results/model_comparison.csv` for the actual model performance metrics.

## Deliverable

A complete NLP sentiment classification notebook with trained models, evaluation results, and a live prediction helper.