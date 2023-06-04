Amazon Web Scraper

This project is a Python script that demonstrates web scraping using BeautifulSoup to extract product details from the Amazon website. It retrieves information such as product title, price, ratings, reviews, and availability for a given search query. Later the data is stored to S3 bucket.


Prerequisites

Before running the script, make sure you have the following:

Python 3.x installed on your system.
Required Python libraries installed: BeautifulSoup, requests, pandas, numpy.
How to Use
Clone or download the script to your local machine.

Open the script in a Python IDE or text editor.

Configure the script parameters:

URL: Specify the Amazon search URL for the desired product.
HEADERS: Set the appropriate headers for the HTTP request.
Run the script.

The script will scrape the product details from the Amazon search page and store them in a Pandas DataFrame.

The DataFrame will be cleaned by dropping rows with missing titles.

The cleaned DataFrame will be saved as a CSV file named amazon_scrapped_data_devesh.csv.

You can customize the script to extract additional information or modify the data handling process according to your needs.


Additional Notes

The script uses BeautifulSoup and requests libraries to scrape the web page and extract relevant data.
It defines several helper functions to extract specific information such as title, price, ratings, reviews, and availability.
The scraped data is stored in a dictionary and then converted into a Pandas DataFrame for further processing.
The script performs data cleaning by dropping rows with missing titles.
The cleaned DataFrame is saved as a CSV file for future analysis or use.
Please note that web scraping should be done responsibly and in compliance with the website's terms of service. Be aware of any legal or ethical considerations when scraping data from websites.

Thank You.





