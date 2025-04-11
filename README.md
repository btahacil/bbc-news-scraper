# 📰 bbc-news-scraper

A Python-based web scraper that collects the latest headlines, summaries, article links, and image URLs from the **Science & Environment** section of [BBC News](https://www.bbc.com/news/science_and_environment).  
The data is saved to a structured `CSV` file for further analysis or use.

---

## 🚀 Features

- 📌 Extracts:
  - Article title
  - Summary/description
  - Full article link
  - Main image URL
- 🗃️ Saves the data into a structured CSV file (`bbc_news.csv`)
- ⚡ Uses **Playwright** for fast and reliable page automation
- 🔄 Built with **asynchronous Python** (`async/await`) for efficiency

---

## 🧠 Technologies Used

- 🐍 Python 3
- 🎭 Playwright (headless browser automation)
- 🔁 asyncio
- 📄 csv

---

## 📦 Output Example

The scraped data is saved in this format:

```
| Title            | Summary           | Link           | Image URL     |
|------------------|-------------------|----------------|---------------|
| NASA discovers… | New evidence shows… | https://...   | https://...   |
```

---

## 🛠️ How to Run

### 1. Install dependencies:

```bash
pip install playwright
playwright install
```

### 2. Run the scraper:

```bash
python main.py
```

✅ The scraper will launch, extract news articles from BBC, and save the data to `bbc_news.csv`.

---

## 👤 Author

> Developed by [@btahacil](https://github.com/btahacil) — building smart automation tools with Python & passion.  
Feel free to ⭐ the repo if you find it useful or open an issue if you have ideas!

---
