# 📰 News Headline Web Scraper

Automated Python-based tool that scrapes and filters top news headlines from a public website (e.g., BBC News) using BeautifulSoup and `requests`.

---

## 🎯 Objective
To collect top headlines from a news website automatically and filter them based on relevant keywords.

---

## 🛠️ Tools Used
- Python
- `requests`
- `BeautifulSoup`
- `argparse`
- `logging`

---

## 📦 Features
- Scrapes headlines (`<h2>`, `<h3>`) from any news site (default: BBC News).
- Filters news based on keywords like: `India`, `Technology`, `World`, `Education`, `Health`.
- Saves the output in a timestamped `.txt` file.
- Logs scraping activity to `scraper.log`.
- Custom URL support via command-line argument.

---

## 🚀 How to Run

### 📌 Requirements
```bash
pip install requests beautifulsoup4

---

## screenshot
![screenshot](https://github.com/user-attachments/assets/ab8f853b-b085-4d1f-b233-8611098bda73)

