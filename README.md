<!-- Add an HTML tag with the image -->
<img src="/assets/img/marketing.JPEG" alt="Cover Image">

Web Scraping Project

This Python script performs web scraping on a specific URL (https://milikispace.co.ke/projects/). It extracts data related to project titles from multiple pages and saves it into a CSV file named milikispace.csv.

Libraries Used
- os: Provides operating system-related functionalities.
- pandas: Used for data manipulation and CSV file creation.
- BeautifulSoup from bs4: A tool for scraping information from web pages.
- requests: Enables fetching HTML content from URLs

How the Script Works
The script iterates through multiple pages of the specified URL and extracts project titles by parsing the HTML content. It then performs cleaning operations on the extracted data to remove unnecessary characters and spaces. Finally, it stores the cleaned data into a CSV file.
