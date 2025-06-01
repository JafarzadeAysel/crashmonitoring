# APA.az News Scraper

This project is a Python-based web scraper that collects news data from the Azerbaijani news site [APA.az](https://apa.az), specifically from search results related to **"qəza"** (accidents). It extracts titles, publication dates, image links, and main text content from each news article and exports the data in a structured format using a pandas DataFrame.

## 📌 Features

- Scrapes multiple pages of search results (`page=1` to `page=10`)
- Extracts individual news article URLs
- Collects:
  - 📰 Title
  - 🗓️ Date of publication
  - 🖼️ Image link
  - 📄 Full text of the news
- Cleans and processes the extracted text
- Exports results as a pandas DataFrame (you can easily convert to CSV or Excel)

## 🛠️ Technologies Used

- Python 3
- `requests`
- `BeautifulSoup` (`bs4`)
- `pandas`
- `lxml` parser


⚠️ Disclaimer
This project is for educational purposes only. Please check and respect APA.az's Terms of Service before using or deploying any large-scale scraping.
