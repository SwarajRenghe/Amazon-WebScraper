# Amazon-WebScraper
A web scraper that extracts data about the bestselling books on Amazon. Written in python.

### Some Details
The repo includes two files, `com_bestseller.py`, which scrapes the international Amazon website, and `in_bestseller.py`, which scrapes the Amazon India website. The list of the 100 top selling books is retrieved from either side, even if the results are on separate pages on Amazon, and compiled into a CSV file stored in a folder named *output*. The CSV file can be viewed in any spreadsheet application. 

## Running the Program

- The only non-native depenency required is the BeautifulSoup library, which can be installed on lInux with the following command.
  - `pip3 install beautifulsoup4`
- Run the program using the following command
  - `python3 [filename].py`
- Make sure you have an active internet connection (can be verified using linux ping)
