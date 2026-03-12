# Banks ETL Project

## What it does
An ETL (Extract, Transform, Load) pipeline that extracts data on the 
World's Largest Banks from Wikipedia, transforms it by converting 
market capitalization into multiple currencies, and loads it into 
both a CSV file and a SQLite database.

## Built As Part Of
Built as part of the [IBM Data Engineering Foundations Specialization](https://www.coursera.org/specializations/data-engineering-foundations) — IBM × Coursera

## Features
- Extracts real world banking data from Wikipedia using web scraping
- Transforms market capitalization data into GBP, EUR, and INR
- Loads processed data into a CSV file and SQLite database
- Runs SQL queries on the database
- Logs every stage of the ETL process with timestamps

## Technologies Used
- Python
- Pandas
- NumPy
- BeautifulSoup
- SQLite3
- Requests

## Files
- Banks_Project.py — Main ETL script
- exchange_rate.csv — Currency exchange rates
- Largest_banks_data.csv — Output CSV file
- Banks.db — SQLite database
- code_log.txt — Log file generated on running the script

## How to Run
1. Install dependencies:
   pip install requests pandas numpy beautifulsoup4
2. Open the project folder in VS Code using Open Folder
3. Run the script:
   python Banks_Project.py
