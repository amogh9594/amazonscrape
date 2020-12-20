# Amazon Scrape
Web scraping helps in automating data extraction from websites. In this tutorial, we will build an Amazon scraper for extracting product details and pricing. We will build this simple web scraper using Python and SelectorLib and run it in a console.

We will use Python 3 for this Amazon scraper. The code will not run if you are using Python 2.7. To start, you need a computer with Python 3 and PIP installed in it.

### Install Packages
* Python Requests, to make requests and download the HTML content of the Amazon product pages
* SelectorLib python package to extract data using the YAML file we created from the webpages we download

Create a folder called amazon-scraper and paste your selectorlib yaml template file as *selectors.yml.

Let’s create a file called *amazon.py and paste the code below into it. All it does is

* Read a list of Amazon Product URLs from a file called *urls.txt
* Scrape the data
* Save the data as a JSON Lines file
* You can start your scraper by typing the command:  python3 amazon.py

Let’s create a file *searchresults.py and paste the code below into it. Here is what the code does

* Open a file called *search_results_urls.txt and read search result page URLs
* Scrape the data
* Save to a JSON Lines file called *search_results_output.jsonl
* You can start your scraper by typing the command:python3 searchresults.py
* Once the scrape is complete you should see a file called search_results_output.jsonl with your data.
* Here is an example for the URL : https://www.amazon.com/s?k=laptops


![Tinkter](https://dominik-spieler.com/wp-content/uploads/2019/03/PythonBrowserBot-2-740x414.png)
