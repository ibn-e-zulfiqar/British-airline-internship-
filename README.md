# British-airline-internship

A simple Python script that scrapes airline passenger reviews from [Skytrax](https://www.airlinequality.com/) and exports the cleaned data to an Excel file — great for beginners exploring web scraping, data cleaning, and automation.

---

## 📌 Features

- Scrapes multiple reviews: title, author, date, rating, and full review text
- Cleans and structures the data with `pandas`
- Saves the dataset to an `.xlsx` file
- Automatically appends new data if the Excel file already exists

---

## 🛠 Tech Stack

- `BeautifulSoup` – for HTML parsing
- `requests` – to fetch webpage content
- `pandas` – for data manipulation and Excel export
- `openpyxl` – for writing to `.xlsx` files


