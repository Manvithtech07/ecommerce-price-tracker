# "Live" Laptop Price Tracker - A complete end to end data analytics project

**Project Status:** In Progress (Phase 1: Web Scraping - Complete)

---

### 1. The Business Problem
In the hyper-competitive Indian mobile phone market, how do prices, features, and ratings for top models compare? This project builds an automated data pipeline to scrape, store, and visualize this market data to answer key business questions:
* What is the average price for a "flagship killer" (e.g., >8GB RAM)?
* Which brand (Samsung, Xiaomi, Realme, etc.) has the best average user rating?
* What is the price-to-rating ratio for the top 20 phones?
* How do these metrics change over time?

### 2. Tech Stack & Pipeline
This project is an end-to-end pipeline that transforms raw web data into actionable business insights.

| Phase | Technology | Purpose |
| :--- | :--- | :--- |
| **1. Data Extraction** | **Python** (`requests`, `BeautifulSoup`) | Scrapes live data from `91mobiles.com`. |
| **2. Data Cleaning** | **Python** (`pandas`, `NumPy`) | Cleans, transforms, and structures the raw data. |
| **3. Data Storage** | **MySQL** | Stores the cleaned data in a relational database. |
| **4. Data Visualization** | **Power BI** | Builds an interactive dashboard for analysis. |

