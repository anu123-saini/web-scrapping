## 📘 Books to Scrape - Web Scraper

This project is a Python-based web scraper that extracts book titles and prices from the [Books to Scrape](https://books.toscrape.com/) website. It crawls through multiple pages and collects data for the first 70 books.

---

### ✅ Features

* Scrapes **book title** and **price** from each listing
* Crawls across multiple pages using the **"Next"** button
* Handles network errors gracefully
* Tracks and prints scraping progress
* Saves data to a `books_data.json` file in **JSON** format

---

### 📂 Output

The output is a file named `books_data.json` containing a list of dictionaries:

```json
[
  {
    "title": "A Light in the Attic",
    "price": "£51.77"
  },
  ...
]

### 📄 Files

| File              | Description                             |
| ----------------- | --------------------------------------- |
| `day_3.py`        | Main script to perform the web scraping |
| `books_data.json` | Output file storing scraped book data   |


