# web-scraping-project
---

-   **Name:** Aditya Raj Sinha
-   **Roll No:** 2301201189

# Project 1 : Live Cricket Score

1.  Attempted scraping ESPN Cricinfo RSS (news only) and live page (blocked).

2.  Used CricAPI (`api.cricapi.com/v1/currentMatches`) with an API key as an alternative.



**How to Run:**

1.  Get a CricAPI key.

2.  Replace the placeholder API key in the code.

3.  Run the cells.



**Data Source:** CricAPI (`api.cricapi.com`)



# Project 2: Top Books Scraper

This project scrapes book information (title, price, and rating) from the website `http://books.toscrape.com/`, saves the data to a CSV file, and performs basic analysis to find the average book price and the best-rated books.

## Project Structure

- `scrape_books(base_url)`: Function to scrape book data from the given URL, handling pagination.
- Data is stored in a pandas DataFrame.
- Data is saved to `books.csv`.
- Calculates and displays the average book price and the best-rated book(s).

## Requirements

- requests
- beautifulsoup4
- pandas

## Usage

1. Run the notebook cells sequentially.
2. The `books.csv` file will be created in the same directory.
3. The average price and best-rated books will be printed to the console.
