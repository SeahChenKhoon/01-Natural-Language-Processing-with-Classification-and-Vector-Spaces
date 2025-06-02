# 01-Natural-Language-Processing-with-Classification-and-Vector-Spaces

A hands-on NLP mini-course exploring preprocessing, word frequencies, vector representations, and logistic regression for sentiment classification using tweet data.

---

## 📘 Overview

This project contains a series of Jupyter Notebooks and utility scripts designed to walk through key NLP concepts including:

- Tweet preprocessing and tokenization
- Word frequency analysis
- Vector space modeling
- Logistic regression for binary sentiment classification
- Data visualization with confidence ellipses

The code is modularized with a `utils.py` file to enable reuse of preprocessing and frequency-building functions across notebooks.

---

## 📁 Directory Structure

```text
.
├── 01_nlp_vector_spaces_intro.ipynb         # Introduction to vector spaces in NLP
├── 02_word_frequencies.ipynb                # Word frequency analysis and exploration
├── 03_logistic_regression_model.ipynb       # Building and evaluating a sentiment classifier
├── 04_vector_spaces_logistic_features.ipynb # Combining NLP vector concepts with logistic models
├── utils.py                                 # Tweet preprocessing and utility functions
├── data/
│   └── logistic_features.csv                # Sample data file used in modeling
```

## 🛠 Requirements
- Python 3.8+
- Jupyter Notebook
- nltk
- numpy
- matplotlib
- sklearn

Install them with:
```bash
pip install numpy matplotlib nltk scikit-learn
```

## 📌 Key Components
### 🔤 Tweet Preprocessing
- Implemented in utils.py, includes:
- Removing tickers, mentions, URLs, hashtags
- Lowercasing and tokenization
- Stopword removal and stemming

### 📊 Frequency and Feature Engineering
- Word-label pair counting with build_freqs
- Vector representation of tweets for logistic regression

### 🤖 Model Training
- Manual logistic regression (gradient descent)
- Evaluation with accuracy and error plots

### 📈 Visualization
- Confidence ellipses showing distribution of vectorized tweet data