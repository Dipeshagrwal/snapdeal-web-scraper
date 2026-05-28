# Snapdeal Men's Sports Shoes Web Scraper

## Project Overview

This project is a Python-based web scraping application developed to extract and analyze men's sports shoes data from Snapdeal.

The scraper collects product information including:

* Product Name
* Brand
* Original Price
* Discounted Price
* Discount Percentage
* Product Rating
* Number of Reviews

The extracted data is stored in CSV format for further analysis and visualization.

---

# Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Matplotlib
* Seaborn

---

# Features

* Multi-page web scraping
* CSV data export
* Brand analysis
* Price distribution analysis
* Rating analysis
* Data visualization using charts

---

# Project Structure

```bash
snapdeal-web-scraper/
│
├── scraper.py
├── snapdeal_mens_sports_shoes.csv
├── requirements.txt
├── README.md
├── .gitignore
└── images/
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/snapdeal-web-scraper.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run Project

```bash
python scraper.py
```

---

# Output

The script generates:

* CSV dataset
* Brand analysis chart
* Price distribution graph
* Top rated brands graph

---

# Sample Output

| Product Name | Brand  | Discounted Price | Rating |
| ------------ | ------ | ---------------- | ------ |
| Campus Shoes | Campus | 827              | 4.2    |

---

# Visualizations

## Top Brands

(Add screenshot here)

## Price Distribution

(Add screenshot here)

## Top Rated Brands

(Add screenshot here)

---

# Challenges Faced

* Dynamic website structure
* Changing HTML class names
* Missing ratings in some products
* Data cleaning and preprocessing

---

# Future Improvements

* Selenium integration
* Export to Excel/JSON
* Streamlit dashboard
* Automated scheduling
* Sentiment analysis on reviews

---

# Author
Dipesh Agrawal
