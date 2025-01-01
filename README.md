**Web Scraping Email Extractor**

This repository contains a Python-based web scraping tool implemented in a Jupyter Notebook. The tool extracts email addresses from a list of web pages using BeautifulSoup and regular expressions, making it an efficient solution for automated data collection.

_Features_
- Scrapes email addresses from web pages.
- Handles errors while navigating through websites.
- Consolidates and removes duplicate emails for a clean output.

_Requirements_
- Python 3.7 or higher
- Required Libraries: beautifulsoup4, requests, re, lxml, urllib
- Install the required libraries using pip: pip install beautifulsoup4 requests lxml

_Usage_
- Clone the repository

  git clone https://github.com/anikakoul/UNESCO-Web-Scraping.git

  cd web-scraping-email-extractor
- Open the Jupyter Notebook: jupyter notebook WebScraping.ipynb
- Update the list of URLs in the code block as needed.
- Run the cells in sequence to extract email addresses from the specified web pages.
- View the final list of unique email addresses in the output.

_Key Functionalities_
- Link Preparation: Adds base URLs to relative links for proper navigation.
- Web Page Parsing: Downloads and parses HTML pages using BeautifulSoup.
- Email Extraction: Identifies and extracts emails using a regex pattern.
- Error Handling: Prints errors encountered during the scraping process.
- Output Cleaning: Removes duplicate emails and consolidates results.

_Example Workflow_
- Input: A list of web pages to scrape.
- Processing:
  - Combines base URLs with relative paths.
  - Navigates to pages and extracts email addresses.
  - Handles exceptions for missing or invalid pages.
- Output: A cleaned list of unique email addresses.
