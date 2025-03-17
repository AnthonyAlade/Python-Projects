# Python-Projects

#  Projects Overview

This repository contains three Python projects focused on web scraping and data cleaning:  

1. Book Scraping 
2. Wikipedia Table Scraping
3. Data cleaning

## Project 1: Book Scraping  

### Description 
This project scrapes books details(title,link,price,instock availability) from an online bookstore. The scraped data is cleaned and saved as a csv file for analysis.

### Data Source
The data was scrapd from Books to scrape (http://books.toscrape.com/catalogue/page-1.html) using python and BeautifulSoup

### Features  
- Scrapes book titles, link to the books and prices from 50 different pages.  
- Saves the scraped data into a CSV file for easy analysis.  

### Technologies Used
This project was developed using anaconda and runs in jupyter notebook. The required libraries are:
- Python
- Requests
- BeautifulSoup
- Pandas  

### Output File
C:\Users\HP\Documents\New folder\scraped1.csv

## Project 2: Wikipedia Table Scraping

### Description 
This Project extracts a structured table from wikipedia and converts it into a csv file for further analysis

### Data Source
The data was scraped from wikipedia(https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue).

### Features  
- Scrapes every row and column from the table  
- Saves the scraped data into a CSV file for easy analysis.


### Technologies Used
This project was developed using anaconda and runs in jupyter notebook. The required libraries are:
- Python
- Requests
- BeautifulSoup
- Pandas


### Output File

C:\Users\HP\Documents\New folder\companies.csv

### License
This project is for educational  purposes onlt. Please check the website terms of service before scraping

## Project 3: Data Cleaning project

### Description 

This repository contains a Python project focused on data cleaning techniques. The goal is to efficiently preprocess raw data to make it suitable for analysis. The datasets contains customer information data with inconsistencies such as

- Duplicate entries
- special characters in the names
- incorrect  format for phone number and address

  ### Features  
- Handling missing values  
- Removing duplicates  
- Standizing names by removing special characters
- Formatting phone numbers to consistent format 
- Cleaning Addresses by spliting it


### Technologies Used
This project was developed using anaconda and runs in jupyter notebook. The required libraries are:
- Python
- Pandas

   

