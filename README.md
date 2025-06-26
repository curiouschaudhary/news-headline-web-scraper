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

  # Screenshot
  ![screenshot](https://github.com/user-attachments/assets/d996ee56-2737-4fa7-9e72-5f9b1918a5b9)


---

## 🚀 How to Run

### 📌 Requirements
```bash
pip install requests beautifulsoup4

