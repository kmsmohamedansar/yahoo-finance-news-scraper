# yahoo-finance-news-scraper

# 📈 Yahoo Finance News Scraper

A Python-based web scraping project that uses **Selenium** and **BeautifulSoup** to extract the latest news headlines, article content, publication dates, and authors from the Yahoo Finance homepage.

---

## 🧠 Project Overview

This project scrapes real-time news articles from Yahoo Finance, capturing JavaScript-rendered content using a headless browser. The extracted data is structured into a clean CSV for downstream tasks like sentiment analysis, topic modeling, or financial trend detection.

---

## 🚀 Features

- ✅ Headless web scraping using Selenium + Chromium in Google Colab
- ✅ Captures dynamic, JavaScript-rendered headlines and article data
- ✅ Extracts:
  - News headline
  - Article URL
  - Published date
  - Author name
  - Full article content
- ✅ Stores all data in a `pandas` DataFrame and exports to CSV

---

## 🛠️ Tech Stack

| Tool            | Purpose                               |
|-----------------|----------------------------------------|
| Python          | Core programming language              |
| Selenium        | Automates browser to load JS content   |
| BeautifulSoup   | Parses HTML and extracts elements      |
| Pandas          | Stores and exports structured data     |
| Google Colab    | Cloud environment for execution        |

---

## 📁 Output

CSV file (`yahoo_finance_news_detailed.csv`) with the following columns:
- `headline`
- `date`
- `author`
- `content`
- `url`

---

## 🧪 Sample Use Cases

- News sentiment tracking
- Financial news classification
- LLM-powered summarization
- Data journalism or newsletter curation

---

## 🔗 Notebook

📌 [View the full Colab Notebook](https://colab.research.google.com/drive/1krqeQ5gLN4JISQM9Lazd2c5_yhEcuABY)

---

## 📌 Note

> This project is for educational and non-commercial use only. Please respect website scraping policies and terms of service.

---

## 📬 Contact

**Mohamed Ansar Kader Meera Sahib**  
[LinkedIn](https://www.linkedin.com/in/mohamedansar97) | [GitHub](https://github.com/your-username)  

---

