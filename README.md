# Zillow Loans

Notebook project for scraping and organizing mortgage loan-rate data.

## Project Overview

This project collects mortgage loan-rate information and turns it into a structured CSV dataset. The notebook separates loan products into categories, extracts rate and APR values, and adds the scrape date so the exported data can be treated as a point-in-time snapshot.

## Data Collected

The notebook organizes the scraped loan information into three main groups:

- Conforming loans
- Government loans
- Jumbo loans

For each product type, the workflow focuses on fields such as loan type, program name, rate, APR, and scrape date.

## Notebook Structure

- Scrape or load mortgage-rate information
- Parse conforming loan products
- Parse government loan products
- Parse jumbo loan products
- Combine extracted records into a pandas DataFrame
- Add the scraping date
- Export the result to CSV

## Output

- `09-30-2023.csv` - exported mortgage-rate snapshot.

## Files

- `zillow.ipynb` - notebook with scraping, parsing, cleaning, and export steps.
- `09-30-2023.csv` - generated data file.

## Tools

Python, requests, BeautifulSoup, pandas, time, and Jupyter Notebook.

## Notes

This project is useful as a small example of web scraping, table construction, and creating a reproducible dated data extract from a public source.
