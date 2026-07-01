# Zillow Loans

Notebook project for collecting and reviewing mortgage loan-rate data from Zillow.

## Project Goal

The goal is to scrape loan-rate information, organize it into a tabular format, and export the result for later analysis. The project focuses on loan types, loan programs, interest rates, and APR values.

## Files

- `zillow.ipynb` - notebook with the scraping and data-preparation workflow.
- `09-30-2023.csv` - exported loan-rate data.

## Workflow

1. Load the source page/data.
2. Extract loan program information.
3. Parse rates and APR values.
4. Store the cleaned results in a CSV file.

## Output

The final dataset includes loan program details and rate/APR values that can be compared across available mortgage products.

## Tools

Python, pandas, and Jupyter Notebook.
