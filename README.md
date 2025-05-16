# 🛒 Amazon Product Scraper and Analyzer

This project is a **Python web scraper** that extracts product data from **Amazon.com** based on a search keyword (e.g., *PlayStation 4*), processes and cleans the data using `pandas`, and then performs exploratory data analysis (EDA) including visualizations of ratings, prices, and review counts.

> ⚠️ **Disclaimer**: This project is for educational purposes only. Scraping Amazon violates their [Terms of Service](https://www.amazon.com/gp/help/customer/display.html?nodeId=508088). Use responsibly and avoid running this on production or commercial systems.

---

## 📌 Features

- Scrapes multiple Amazon search result pages.
- Extracts detailed product information:
  - ✅ Title
  - 💲 Price
  - ⭐ Rating
  - 💬 Review Count
  - 🚚 Availability
- Cleans and transforms data using `pandas`.
- Visualizes rating distribution using `matplotlib` and `seaborn`.
- Outputs a CSV file (`amazon_data.csv`) with all scraped and cleaned data.

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have Python 3.7+ installed.

Install required packages:

```bash
pip install -r requirements.txt
