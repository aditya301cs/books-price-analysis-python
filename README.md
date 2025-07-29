# 📚 Books Price Analysis (Python Web Scraping + EDA)

This project demonstrates how to scrape data from an e-commerce-like website and perform complete exploratory data analysis (EDA) using Python.

## 🔍 About the Project

We scrape data from [BooksToScrape.com](https://books.toscrape.com), a mock website for web scraping practice. The project involves:

- Collecting book titles, prices, availability, ratings, and links
- Converting GBP prices to INR using a live exchange rate API
- Exporting the scraped data to a structured CSV file
- Performing detailed data analysis with visualizations

## 🧰 Tech Stack

- Python 3
- Jupyter Notebook
- Libraries: `requests`, `BeautifulSoup`, `pandas`, `matplotlib`, `seaborn`
- API: Frankfurter.app (live currency conversion)

## 📊 Key Features

- Scrapes 1000 books across 50 pages
- Handles dynamic conversion of currencies using API
- Filters books under ₹500
- Plots rating distributions, availability ratios, and price trends
- Top 10 most expensive & cheapest books
- Correlation heatmap between numeric fields

## 💾 Outputs

- `books.csv` – cleaned and converted dataset
- `BooksToScrape_WebScraping.ipynb` – scraping logic
- `Books_EDA.ipynb` – complete EDA notebook

## 📷 Sample Visualizations

![Histogram of Prices](images/price-distribution.png)
![Rating Countplot](images/rating-distribution.png)

## 🚀 Getting Started

```bash
git clone https://github.com/aditya301cs/books-price-analysis-python.git
cd books-price-analysis-python
pip install -r requirements.txt
