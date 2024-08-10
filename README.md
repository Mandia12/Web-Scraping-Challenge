# Mars Data Scraping and Analysis Project

## Overview
This project focuses on web scraping and data analysis of Mars-related information from the Mars News website. It is divided into two main parts: Mars News Scraping and Mars Weather Data Analysis.

## Dataset
The project leverages data from the Mars News website:
https://static.bc-edx.com/data/web/mars_news/index.html

This website contains:
1. Mars news articles
2. Mars weather data table

## Steps

1. **Mars News Scraping:**
   * Utilized BeautifulSoup, Selenium, and Splinter to access the Mars News website.
   * Implemented a loop to scrape article titles and preview texts from the website.
   * Organized the scraped data into a Python dictionary.
   * Exported the dictionary to a JSON file for future use.

2. **Mars Weather Data Analysis:**
   * Accessed the Mars weather data on the same website using web scraping tools.
   * Extracted data from a table on the website.
   * Performed analysis to answer key questions about Mars:
     - Number of months on Mars
     - Number of Martian days in the dataset
     - Coldest and warmest months on Mars
     - Months with highest and lowest atmospheric pressure
     - Estimation of Earth days in a Martian year

## Tools
* BeautifulSoup for parsing HTML
* Selenium for web browser automation
* Splinter for interacting with websites
* Python for data processing and analysis

## Results

The project delivers insights into Mars' climate and news based on data from the Mars News website:

1. Mars has 12 months.
2. The dataset contains information for 1,867 Martian days.
3. Temperature extremes:
   * Coldest month: Month 3
   * Warmest month: Month 8
4. Atmospheric pressure extremes:
   * Highest pressure: Month 9
   * Lowest pressure: Month 6
5. A Martian year is approximately 675 Earth days.

These findings provide valuable information about Mars' climate patterns and help in understanding the planet's environmental conditions, all derived from the data available on the Mars News website.
