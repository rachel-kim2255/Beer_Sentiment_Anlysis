# 🍻 IPA vs Lager Review Sentiment Analysis
**🛠️ VADER, TextBlob, Praw(Reddit API)**  
<br>
📎 Rachel Kim  
📅 Date: 2025.03  
📚 Individual Project
<br>

📝 This project performs sentiment analysis on beer reviews collected from Reddit using two sentiment analysis libraries: 
**VADER** and **TextBlob**. The reviews are filtered based on two popular beer types: **IPA 🍺** and **Lager 🍺**. The goal of this project is to assess the sentiment of beer reviews and provide insights into how users feel about different beer types.
<br>
<br>

**Result Summary** : Both VADER and TextBlob sentiment analyses showed that **Neutral sentiment dominated in Reddit posts about IPA and Lager (over 50%).**
Lager received slightly more positive sentiment than IPA, while IPA showed higher negative sentiment, likely due to its bold flavor profile.
This suggests that Reddit users tend to share comparative or descriptive reviews rather than strong emotional reactions.  
<br>
**Suggestions** : 
- The dominance of neutral sentiment indicates a relatively low level of emotional engagement with beer brands or preferences, suggesting an opportunity to enhance emotional storytelling in marketing.
- IPA, which received more negative sentiment than Lager, may benefit from targeted marketing aimed at niche or enthusiast audiences who enjoy bold flavors.
- In contrast, Lager showed slightly higher positive sentiment, indicating its potential appeal to a broader, general audience.
- Since Reddit users tend to share descriptive rather than emotional opinions, brands that offer unique, emotionally resonant experiences and flavors may have greater influence and engagement within the community.

<br>
<br>
## 📂 Project Files

- **beer_reviews_praw.csv**, **beer_reviews_json.csv**: The dataset containing beer reviews, including the title, text, score, and the corresponding keyword (IPA, Lager).
- **beer_reviews_with_sentiment.csv**: The result dataset after sentiment analysis, which includes VADER and TextBlob sentiment labels and scores.
  (columns: Subreddit, Keyword, Title, Text, Score, VADER_Score, VADER_Sentiment_Label, TextBlob_Score, TextBlob_Sentiment_Label,	Importance_Score)
- **IPA vs Lager Analyzing Reddit Discussions.ipynb**: Jupyter notebook containing the entire analysis process
<br>

## 📂 Libraries Used
- **pandas**: Data manipulation and analysis.
- **praw**: A Python library that makes it easy to crawl data from Reddit.
- **requests**: Sending HTTP requests to retrieve data from Reddit.
- **VADER**: A sentiment analysis tool specifically tuned for social media text.
- **TextBlob**: A text processing library for processing textual data, including sentiment analysis.

