# Sample Directive: Scrape Website

This directive defines the SOP for scraping a website.

## Goal
Extract structured data from a single website URL.

## Inputs
- `url`: The URL of the website to scrape.

## Tools/Scripts
- `execution/scrape_single_site.py`: The script that performs the actual scraping.

## Step-by-Step Instructions
1. Accept the `url` from the user.
2. Run the `execution/scrape_single_site.py` script with the `url` as an argument.
3. Save the results to the `.tmp/` directory.
4. Notify the user with the path to the extracted data.

## Edge Cases
- Website is down: Log the error and notify the user.
- URL is invalid: Ask the user for a valid URL.
