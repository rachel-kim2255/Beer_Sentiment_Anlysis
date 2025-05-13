# CSIS-4280 Assignment 2
300394050 Rachel Kim

## Beer Review Sentiment Analysis

This project performs sentiment analysis on beer reviews collected from Reddit using two sentiment analysis libraries: 
**VADER** and **TextBlob**. The reviews are filtered based on two popular beer types: **IPA** and **Lager**. The goal of this project is to assess the sentiment of beer reviews and provide insights into how users feel about different beer types.

## Project Files

- 'beer_reviews_praw.csv', 'beer_reviews_json.csv': The dataset containing beer reviews, including the title, text, score, and the corresponding keyword (IPA, Lager).
- 'beer_reviews_with_sentiment.csv': The result dataset after sentiment analysis, which includes VADER and TextBlob sentiment labels and scores.(columns: Subreddit, Keyword, Title, Text, Score, VADER_Score, VADER_Sentiment_Label, TextBlob_Score, TextBlob_Sentiment_Label,	Importance_Score)
- 'Assignment2 300394050.ipynb': Jupyter notebook containing the entire analysis process


## Libraries Used
- **pandas**: Data manipulation and analysis.
- **praw**: A Python library that makes it easy to crawl data from Reddit.
- **requests**: Sending HTTP requests to retrieve data from Reddit.
- **VADER**: A sentiment analysis tool specifically tuned for social media text.
- **TextBlob**: A text processing library for processing textual data, including sentiment analysis.

