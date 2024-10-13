# Sentiment Analysis Project

## Overview
This project performs sentiment analysis on product reviews using Natural Language Processing (NLP) techniques. The goal is to classify reviews into positive, negative, or neutral sentiments, providing insights into customer opinions about products.

## Technologies Used
- Python
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Pandas
- Matplotlib
- WordCloud
- Jupyter Notebook

## Dataset
The dataset used for this project consists of product reviews. Each review is labeled as either positive, negative, or neutral.

## NLP Techniques
The project employs various NLP techniques, including:

1. **Tokenization**: Splitting text into individual words (tokens) for analysis.
2. **Lemmatization**: Reducing words to their base form to ensure similar meanings are grouped together.
3. **TF-IDF (Term Frequency-Inverse Document Frequency)**: A statistical measure used to evaluate the importance of a word in a document relative to a corpus.
4. **Sentiment Analysis**: Classifying the sentiment expressed in reviews using a machine learning model.

## Project Steps
1. **Data Cleaning**: Removed special characters and irrelevant information from the reviews.
2. **Tokenization**: Tokenized the cleaned text into individual words.
3. **Lemmatization**: Reduced words to their base form.
4. **TF-IDF Vectorization**: Converted the tokens into numerical features.
5. **Model Training**: Trained a Logistic Regression model to classify sentiments.
6. **Visualization**: Generated word clouds and other visualizations to represent the sentiment analysis results.

