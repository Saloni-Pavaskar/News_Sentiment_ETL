# News Sentiment Analysis ETL Pipeline

This project demonstrates an **ETL pipeline** that extracts news data using NewsAPI, cleans the text, performs sentiment analysis using **TextBlob**, and stores the results in a **SQLite database**.

---

## Features
- Extracts news articles using the NewsAPI.
- Cleans the text (removes URLs and special characters).
- Performs **sentiment analysis** on article titles.
- Stores cleaned data and sentiment scores in a **SQLite database**.
- Generates sentiment summary reports using SQL queries.
- Logs ETL execution status using Python’s `logging` module.

---

## Tech Stack
- **Python** (pandas, requests, TextBlob)
- **SQL** (SQLite via SQLAlchemy)
- **ETL** workflow: Extract → Transform → Load
- **Jupyter Notebook** for step-by-step execution

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/News_Sentiment_ETL.git
