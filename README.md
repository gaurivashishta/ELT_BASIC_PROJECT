📘 Overview

This project demonstrates a complete ETL (Extract, Transform, Load) data pipeline built using Python.
It extracts real-world GDP data from a Wikipedia source, transforms it into a structured format, and loads it into both a SQLite database and a CSV file for further analysis.

This project highlights practical data engineering concepts like data extraction, cleaning, transformation, and storage automation.
-------------------------------------------------------------------------------------------------------------------------------------------------

Tech Stack

Programming Language: Python

Libraries Used: BeautifulSoup, Requests, Pandas, NumPy, SQLite3, Datetime

Concepts Covered: ETL Pipeline, Data Extraction, Transformation, Database Loading, Logging

-----------------------------------------------------------------------------------------------------------------------------------
Features

Web Scraping: Extracted GDP data of all countries from a Wikipedia table using BeautifulSoup.

Data Transformation: Converted GDP values from millions to billions (USD), ensuring consistent numeric formatting.

Data Loading: Stored the cleaned data into both a local CSV file and a SQLite database table.

Query Execution: Retrieved and filtered countries with GDP greater than or equal to 100 billion USD.

Automated Logging: Maintained progress logs at every stage of the ETL process.

-------------------------------------------------------------------------------------------------------------------------

🧠 Skills Demonstrated

Data Engineering fundamentals (ETL workflow)

Data cleaning and transformation using Pandas

Working with databases (SQLite)

Data validation and automation using Python scripts

Logging for process transparency and debugging
