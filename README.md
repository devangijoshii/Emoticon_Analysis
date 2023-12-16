# Emoji Sentiment Analysis Project

## Overview

This project explores the emotional expressions in tweets on Twitter using emojis. The goal is to understand the emotional tone of conversations and unveil patterns and trends in social media interactions. Emojis play a crucial role in conveying sentiments, and this analysis provides valuable insights into the emotional landscape of Twitter.

## Project Components

1. **Data Collection:**
   - The primary data source is Twitter, with a diverse dataset collected from Kaggle, a well-established platform for accessing datasets.
   - The dataset is available in CSV format, containing approximately 20,000 to 28,000 tweets.

2. **Data Preprocessing:**
   - Text data undergoes several preprocessing steps, including lowercasing, URL and username replacement, removing non-alphabets, short words, stopwords, and lemmatization.

3. **Emoticon Frequency Analysis:**
   - Investigates the frequency of specific emojis within each context.
   - Visualizes the emoticon frequency within each context using a bar chart.

4. **Contextual Segmentation (Topic Modeling):**
   - Utilizes Latent Dirichlet Allocation (LDA) to segment tweets into different topics or contexts.
   - Identifies the top terms for each topic and displays the distribution of tweets across topics.

5. **Sentiment Analysis:**
   - Performs sentiment analysis using NLTK's SentimentIntensityAnalyzer.
   - Visualizes the distribution of overall sentiments and sentiment based on emojis.

6. **t-SNE Visualization of Emoji Embeddings:**
   - Applies t-distributed Stochastic Neighbor Embedding (t-SNE) to visualize emoji embeddings in 2D space.

7. **Emoticon Meaning Analysis:**
   - Employs spaCy's pre-trained model to obtain embeddings for selected emojis.
   - Visualizes the embeddings using plotly express.

8. **Sentiment Analysis Within Contexts:**
   - Analyzes sentiment within each context and visualizes the distribution using seaborn and matplotlib.

9. **Emoticon Frequency Within Contexts:**
   - Explores the frequency of target emojis within different contexts and visualizes the results using a stacked bar chart.

## Requirements

- Python 3.x
- Libraries: pandas, matplotlib, seaborn, nltk, emoji, spacy, scikit-learn, plotly, gensim

## How to Run

1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run each Jupyter notebook or Python script for specific analyses.

Feel free to explore and contribute! Your insights are valuable in deciphering the nuances of emoji usage on Twitter.
