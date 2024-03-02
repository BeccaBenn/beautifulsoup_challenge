Mars Web Scraping and Data Analysis Project
Background
This is Challenge 11 for UCSB Data Analytics Bootcamp

This project aims to scrape data from two sources related to Mars: news articles from the Mars News website and weather data from the Mars Temperature Data Site. The scraped data will be analyzed to gain insights into Martian weather patterns and provide information about the latest news related to Mars.

Files
The project consists of two Jupyter Notebooks:

part_1_mars_news.ipynb: This notebook focuses on scraping news articles from the Mars News website.
part_2_mars_weather.ipynb: This notebook focuses on scraping and analyzing Mars weather data.
Part 1: Scrape Titles and Preview Text from Mars News
Automated browsing is used to visit the Mars News website.
Beautiful Soup is employed to extract text elements from the website.
Titles and preview text of news articles are scraped and stored in Python dictionaries.
The scraped data is stored in a Python list and optionally exported to a JSON file.
Part 2: Scrape and Analyze Mars Weather Data
Automated browsing is used to visit the Mars Temperature Data Site.
Beautiful Soup is utilized to scrape the data from the HTML table.
The scraped data is assembled into a Pandas DataFrame with appropriate column headings.
Data types are examined and converted as necessary.
The dataset is analyzed to answer specific questions regarding Martian weather patterns.
Visualizations, such as bar charts, are created to illustrate the analysis results.
The DataFrame is exported to a CSV file.
Instructions
Open the respective Jupyter Notebooks for each part of the project.
Follow the instructions provided in the notebooks to execute the scraping and analysis tasks.
Review the results, including scraped data and analysis findings, within the notebooks.
Optionally, export the scraped data to JSON files (Part 1) and the analyzed data to a CSV file (Part 2) for sharing and further use.
References
Mars News website: Provides news articles related to Mars.
Mars Temperature Data Site: Contains data on Martian weather.
Images are used according to the JPL Image Use Policy, courtesy NASA/JPL-Caltech.
