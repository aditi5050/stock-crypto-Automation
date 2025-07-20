# stock-crypto-Automation
Stock & Crypto News Scraper, Summarizer & Sentiment Analyzer
An end-to-end NLP pipeline that scrapes financial news headlines, summarizes the articles using transformer models, and performs sentiment analysis to classify market mood — tailored for both stocks and cryptocurrencies.
# Features
🔎 News Scraping: Retrieves the latest headlines from Google News using dynamic ticker-based search (e.g., "AAPL stock", "Ethereum crypto").

🧠 Text Summarization: Uses Hugging Face BART to generate concise, investor-friendly summaries from raw article content.

💬 Sentiment Analysis: Applies FinBERT and DistilBERT to label each article as Positive, Neutral, or Negative with probability scores.

📁 Export to CSV: Saves all summaries and sentiment results into structured CSV files (assetsummaries.csv, ethsummaries.csv).
Tech Stack
Python 3

BeautifulSoup – Web scraping

transformers – Summarization (BART), Sentiment (FinBERT)

pandas – Data handling

requests, re – HTTP and parsing

csv – Exporting results

# How to Run :
# Step 1: Install dependencies
pip install beautifulsoup4 pandas requests transformers

# Step 2: Run the script
python scrapesummarizesentiment.py
