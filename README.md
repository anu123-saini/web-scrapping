## 📘 Books to Scrape - Web Scraper

This Python script scrapes book titles and prices from the [Books to Scrape](https://books.toscrape.com/) website. It collects data from multiple pages until it gets 70 books, and saves the results in a JSON file.

---

### ✅ Features

* Scrapes book **title** and **price**
* Follows the **next page** automatically
* Stops after collecting 70 books
* Saves the data to `books_data.json`

---

### 📄 Output

The scraped data will be saved in:

```
books_data.json
```

Example:

```json
[
  {
    "title": "A Light in the Attic",
    "price": "£51.77"
  }
]
```


