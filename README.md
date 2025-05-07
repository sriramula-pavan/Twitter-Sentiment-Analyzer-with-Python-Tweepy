# 🐦 Twitter Sentiment Analysis with Python & Tweepy

This project uses **Twitter’s API** (via Tweepy) and **Natural Language Processing (NLP)** techniques to collect tweets in real-time and analyze their sentiment. It’s a great tool for understanding public opinion on trending topics, brands, or events using real-time social media data.

---

## 📁 File Included
- `Tweeter Code file.ipynb`: Jupyter Notebook containing:
  - Twitter API authentication
  - Live tweet extraction using Tweepy
  - Text cleaning and preprocessing
  - Sentiment classification (Positive / Negative / Neutral)
  - Visualization of sentiment distribution

---

## 🔍 Features
- Live tweet streaming by keyword or hashtag
- Text cleaning (removal of links, mentions, emojis, etc.)
- Sentiment analysis using TextBlob or Vader
- Output includes polarity, subjectivity scores, and label
- Bar charts / pie charts showing sentiment trends

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Tweepy** – to interact with Twitter API
- **TextBlob / VaderSentiment** – for sentiment analysis
- **Pandas / Matplotlib / Seaborn** – for data handling and visualization
- **Jupyter Notebook** – for step-by-step execution and explanation

---

## 📊 Use Cases
- Brand monitoring
- Political campaign tracking
- Event feedback analysis
- Public sentiment research

---

## 🚀 Future Enhancements
- WordCloud generation for most frequent positive/negative terms
- Deploy as a Streamlit or Flask web app
- Language filtering or translation
- Store results in a database for historical trend analysis

---

## 📦 Installation

```bash
pip install tweepy textblob vaderSentiment matplotlib seaborn
Also, ensure you have valid Twitter API credentials (API Key, API Secret, Access Token, Access Token Secret).

 API Setup:
Sign up for a Twitter Developer account.

Create an app and generate API keys.

Store them securely and load via environment variables or directly in your script (not recommended for public repos).



