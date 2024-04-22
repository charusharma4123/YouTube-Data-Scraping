# YouTube Data Scraping Project
## Overview
This repository contains Jupyter Notebooks for scraping data from YouTube videos, specifically focusing on the GeeksforGeeks YouTube channel. The project utilizes Selenium and BeautifulSoup libraries to extract valuable insights such as video titles, upload dates, likes, views, and descriptions.

## Requirements
- Python 3.x
- Selenium
- BeautifulSoup
- ChromeDriver (for Selenium WebDriver)

## Project Structure
- scrape_video_links.ipynb: Jupyter Notebook for scraping video links from the GeeksforGeeks YouTube channel.
- scrape_video_data.ipynb: Jupyter Notebook for scraping data from individual video pages.
- Youtube_data.csv: CSV file containing the video links.
- GFG_ytdata.csv: CSV file containing the data scraped from individual videos.

## Getting Started
- Clone the repository to your local machine.
- Run scrape_video_links.ipynb to scrape video links from the GeeksforGeeks YouTube channel.
- Run scrape_video_data.ipynb to scrape data from individual video pages.
- The scraped data will be stored in GFG_ytdata.csv.

## Notes
- Adjust the code as necessary for different YouTube channels or HTML structures.
- Feel free to explore additional features or enhancements for the scraping process.
