# American Airlines Customer Review Analysis

This Jupyter notebook contains an analysis of customer reviews for American Airlines, using web scraping, data cleaning, exploratory data analysis (EDA), and natural language processing (NLP) techniques.

## Contents

1. Data Collection
   - Web scraping from Skytrax using Python and BeautifulSoup

2. Data Cleaning
   - Handling missing values
   - Removing non-textual elements
   - Text normalization
   - Converting date columns
   - Converting 'Recommended' column to binary values

3. Exploratory Data Analysis (EDA)
   - Ratio of positive and negative reviews
   - Violin plots of ratings for different service aspects
   - Analysis of overall ratings by country

4. Text Analytics
   - Word clouds for positive and negative reviews
   - Sentiment analysis
   - TF-IDF analysis
   - LDA topic modeling

## Key Insights

- The majority of reviews are negative, with issues primarily related to delays, customer service, and baggage handling.
- Sentiment analysis reveals that negative reviews tend to be more subjective than positive ones.
- Topic modeling identified distinct themes in the reviews, including customer service issues, baggage problems, and flight delays.

## Requirements

- Python 3.x
- Libraries: BeautifulSoup, WordCloud, TextBlob, gensim, scikit-learn, pandas, matplotlib, seaborn, plotly, numpy, pyLDAvis

## Usage

Run the cells in order to reproduce the analysis. Make sure to install all required libraries before running the notebook.