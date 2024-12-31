# Sentiment-Analysis-with-NLP
A Python-based project utilizing Natural Language Processing (NLP) techniques to analyze and classify product reviews. The project classifies reviews as **positive**, **negative**, or **neutral** sentiments and includes data preprocessing, sentiment analysis using TextBlob, and insightful visualizations.

## Introduction

This project utilizes customer review data to classify product reviews based on sentiment. It provides a hands-on demonstration of:
- **Text preprocessing** (e.g., cleaning, tokenization, stopword removal).
- **Sentiment analysis** using TextBlob's sentiment polarity.
- **Data visualization** to interpret sentiment distribution across products.

### Key Libraries
- `nltk` for text preprocessing.
- `TextBlob` for sentiment analysis.
- `matplotlib` and `seaborn` for visualizations.

---

## Dataset

The dataset contains nearly 3,000 Amazon customer reviews, star ratings, feedback, and product variants of Alexa devices such as Echo, Echo Dots, and Firesticks. The data was sourced from Kaggle:

```python
import kagglehub

# Download latest dataset
path = kagglehub.dataset_download("sid321axn/amazon-alexa-reviews")
print("Path to dataset files:", path)

```
