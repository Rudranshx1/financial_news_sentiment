# 📰 Financial News Sentiment Analysis

A **Streamlit-based web application** that fetches the latest financial
news and performs **sentiment analysis** using **TextBlob**. The app
assigns a sentiment score and displays it with **color-coded indicators
and emojis** for easy interpretation.

------------------------------------------------------------------------

## 🚀 Features

-   🔎 **Search by Company or Topic**
    -   Enter a keyword (e.g., *Tesla*, *Bitcoin*, *Amazon*) to fetch
        related news.
-   📰 **Fetch Latest Financial News**
    -   Uses the **NewsAPI** to retrieve real-time financial articles.
-   📊 **Sentiment Analysis with TextBlob**
    -   Calculates the **polarity score** (-1 to +1).\
    -   Interprets news as **Positive, Negative, or Neutral**.
-   🎨 **Color-Coded Sentiment Indicators**
    -   🟢 **Positive** → 😊\
    -   🔴 **Negative** → 😞\
    -   🟡 **Neutral** → 😐

------------------------------------------------------------------------

## 🖥️ UI Layout

-   Input field for **search queries** (company name, financial topic).\
-   List of news articles with:
    -   **Title & Description**\
    -   **Sentiment Score with color + emoji**\
-   Divider between each article for better readability.

------------------------------------------------------------------------

## ⚙️ Technical Implementation

-   **News Fetching** → Uses `requests` to call **NewsAPI**.\
-   **Sentiment Analysis** → Uses `TextBlob` for polarity calculation.\
-   **Visualization** → Streamlit displays results with styled Markdown.

------------------------------------------------------------------------

## 📦 Installation

Clone this repository:

``` bash
git clone https://github.com/your-username/financial-news-sentiment.git
cd financial-news-sentiment
```

Install dependencies:

``` bash
pip install streamlit requests textblob
```

Run the app:

``` bash
streamlit run app.py
```

------------------------------------------------------------------------

## 🔑 API Key Setup

This project uses **NewsAPI**.

1.  Get a free API key at <https://newsapi.org>.\
2.  Replace the API key in the code:

``` python
url = f"https://newsapi.org/v2/everything?q={query}&apiKey=YOUR_API_KEY"
```

------------------------------------------------------------------------

## 🔮 Future Enhancements

-   📈 Integration with **stock price movements**\
-   🤖 Use of **advanced NLP models** (BERT, GPT) for deeper sentiment
    insights\
-   📊 Generate **sentiment trend charts** over time

------------------------------------------------------------------------

## 🧑‍💻 Developer

**Rudransh Kumar Ahluwalia**\
MBA FinTech
