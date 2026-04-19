# DistilBERT Sentiment Analysis on IMDb Reviews

## Project Overview

This project fine-tunes the **DistilBERT** model on IMDb movie reviews to perform sentiment analysis and classify the sentiment of individual movie reviews.

## Model Architecture

**DistilBERT** leverages **Masked Language Modeling (MLM)** as its core training mechanism:

- **Masked Language Modeling**: During training, random words in sentences are masked (hidden)
- The model learns to predict these masked tokens by understanding the context from surrounding words
- This approach enables the model to develop a deep understanding of language semantics and syntax
- Fine-tuning on the IMDb dataset adapts these learned representations for sentiment classification tasks

## Key Features

- Fine-tuned on IMDb movie review dataset
- Sentiment classification (positive/negative)
- Efficient model based on BERT distillation
- Pre-trained contextual embeddings

## Dataset

IMDb Movie Reviews - A large corpus of movie reviews with labeled sentiments, ideal for training robust sentiment analysis models.

## Objective

Develop a high-performing sentiment classifier that can accurately determine whether a movie review expresses positive or negative sentiment, leveraging transfer learning from pre-trained language models.

## Predicted text after fine tuning
![Prediction](https://github.com/sawarni99/sentiment-analysis-imdb/blob/main/images/Prediction.png)
