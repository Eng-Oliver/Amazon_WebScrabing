Amazon.eg Product Scraper
Overview:

This project is a simple web scraping script built with Python and Selenium to extract product details (name and price) from Amazon Egypt.
The script:
Opens a specific Amazon Egypt category page.
Waits for product elements to fully load.
Collects each product's title and price (if available).
Prints the results in the console.
Saves all collected data into a CSV file (amazon_products.csv).
Displays the absolute path of the saved file.

Features:
Automated browser control with Selenium.
Scrolls to each product to ensure visibility before extraction.
Gracefully handles missing product titles or prices.
Outputs results both in the terminal and in a structured CSV file.
Works with dynamic web content (JavaScript-rendered pages).

Requirements
Make sure you have the following installed:
Python 3.8+
Google Chrome Browser
ChromeDriver (compatible with your Chrome version)

Required Python packages:
pip install selenium
Usage
Clone this repository or copy the script.

Run the script with:
python amazon_scraper.py


The script will:
Open Amazon Egypt.
Extract product details.
Save them in a file called amazon_products.csv.

Output:

Product: Samsung Galaxy A55 | Price: 15,999.00
Product: Apple iPhone 14 | Price: Not available


CSV File:

title	price
Samsung Galaxy A55	15,999.00
Apple iPhone 14	Not available

Saved Location:
The script will print the full file path at the end, for example:
Data has been saved to: C:\Users\YourName\Projects\amazon_products.csv
