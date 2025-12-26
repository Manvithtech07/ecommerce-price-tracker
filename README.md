# "Live" Laptop Price Tracker - End-to-End Data Engineering Project

**Project Status:** In Progress (Phase 1: Web Scraping - Complete)

## 1. The Business Problem
In the volatile electronics market, how do prices and specs for gaming laptops compare? This project builds an automated data pipeline to scrape, store, and visualize Amazon data to answer:
- What is the best time to buy a gaming laptop?
- Which brand offers the best Price-to-Performance ratio?
- How do ratings correlate with price drops?

## 2. Tech Stack & Pipeline
| Phase | Technology | Purpose |
|-------|------------|---------|
| **1. WebScraping** | **Selenium & BeautifulSoup** | **Scrapes live laptop prices from Amazon.in** |
| 2. Cleaning | Pandas | Cleans and structures raw data (removing currency symbols, etc.) |
| 3. Storage | MySQL | Stores historical price data for trend analysis |
| 4. Visualization | Power BI | Interactive dashboard for insights |

## 3. How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Run the scraper: `python src/amazon_scraper.py`
