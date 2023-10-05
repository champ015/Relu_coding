# Relu_coding
 MAIN TASK In this task we want you to scrape a minimum hundred URL".rs are in the CSV file https://docs.google.com/spreadsheets/d/1BZSPhk1LDrx8ytywMHWVpCqbm8URT xTJrIRkD7PnGTM/edit?usp=sharing. The CSV file contains 1000 rows. Use Selenium or bs4 to Scarpe the following details from the page. 

**Step 1:** Set up your development environment with the necessary libraries (Python latest, BS4/Scrapy/Selenium, requests).

**Step 2:** Create a Python script that does the following:

- Read the CSV file containing the Amazon URLs and ASINs.
- Loop through each URL and ASIN combination.
- For each URL, use either Selenium or BS4 (Beautiful Soup) to scrape the required information:
  - Product Title
  - Product Image URL
  - Price of the Product
  - Product Details
- If a URL returns a 404 error, skip that URL and print it as "URL not available."

**Step 3:** Collect the scraped data for each product into a list of dictionaries.

**Step 4:** After processing 100 URLs (or a multiple of 100), calculate the time it took to complete them and log this information.

**Step 5:** Continue processing the remaining URLs.

**Step 6:** Once all URLs are processed, convert the list of dictionaries into a JSON file.
