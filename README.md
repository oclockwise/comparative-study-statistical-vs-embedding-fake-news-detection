# Comparative Study of Statistical vs Embedding-Based Models for Fake News Detection

## Overview
This project compares traditional machine learning methods and modern deep learning approaches for fake news detection. It evaluates how different text representation techniques impact classification performance.

## Dataset
- News articles labelled as **real or fake**
- Includes textual content used for classification

## Methodology

### 1. Data Preprocessing
- Text cleaning (lowercasing, removing punctuation, stopwords)
- Tokenization of text data
- Handling missing values

### 2. Feature Engineering
- **TF-IDF Vectorization** (statistical approach)
- **Word embeddings / BERT embeddings** (deep learning approach)

### 3. Models Implemented
- Logistic Regression (with TF-IDF)
- BERT Classifier (embedding-based deep learning model)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Key Findings
- TF-IDF with Logistic Regression provides a strong baseline with fast performance
- BERT captures deeper contextual meaning and achieves higher accuracy
- Embedding-based models perform better on complex language patterns

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Transformers (BERT)
- Matplotlib / Seaborn

##  Project Structure
- `notebook.ipynb` – main analysis and modelling
- `data/` – dataset files
- `outputs/` – results and visualizations

## Conclusion
This study highlights the trade-offs between traditional and deep learning models. While statistical models are efficient and simple, embedding-based models offer better performance for nuanced text classification tasks like fake news detection.
