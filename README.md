# Web Scraping Quotes

This repository contains a Python script that scrapes quotes and their authors from the [quotes.toscrape.com](https://quotes.toscrape.com/) website and saves the extracted data to a CSV file.

## Overview

The script uses the `BeautifulSoup` library to parse the HTML content of the webpage and extract the quotes and their corresponding authors. It then stores the data in a CSV file, making it easy to access or analyze the quotes later.

## Requirements

Before running the script, you need to have the following libraries installed:

- `BeautifulSoup` (for parsing HTML)
- `requests` (for making HTTP requests)
- `csv` (to handle CSV file writing)

You can install the necessary libraries using the following pip command:

```bash
pip install beautifulsoup4 requests

Usage
Clone the repository:

bash
Copy
git clone https://github.com/yourusername/web-scraping-quotes.git
Navigate to the project directory:

bash
Copy
cd web-scraping-quotes
Run the Python script to scrape quotes and authors:

bash
Copy
python scraped_quotes.py
The quotes will be saved in a CSV file called scraped_quotes.csv in the same directory.

Code Explanation
The script sends a GET request to the URL https://quotes.toscrape.com/ using the requests library. It then uses BeautifulSoup to parse the HTML of the page and find all quotes (inside <span class="text">) and their authors (inside <small class="author">). The quotes and authors are written to a CSV file named scraped_quotes.csv.

Example Output (scraped_quotes.csv)
csv
Copy
QUOTES,AUTHORS
"The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking.",Albert Einstein
"It is our choices that show what we truly are, far more than our abilities.",J.K. Rowling
"Do not dwell in the past, do not dream of the future, concentrate the mind on the present moment.",Buddha
Contributing
If you'd like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

vbnet
Copy

This version has the proper formatting with sections separated, code blocks, and bullet points for readability. Let me know if you need anything else!
