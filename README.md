# 📰 News Headlines Scraper

A simple Python script that scrapes the latest news headlines from a given URL and saves them to a `.txt` file using `requests` and `BeautifulSoup`.

## 📌 Features

- Scrapes headlines from HTML tags like `<h2>` and `<h3>`
- Removes duplicate headlines
- Saves results with a timestamp
- Handles network and parsing errors gracefully


## 🧰 Requirements

- Python 3.x
- Required libraries:
  - `requests`
  - `beautifulsoup4`

### 🔧 Installation

Install dependencies using pip:

```bash
pip install requests beautifulsoup4
