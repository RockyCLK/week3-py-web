# week3-py-web
# Web Analysis of IMDb Movies

This project performs web analysis on IMDb movies using Python, BeautifulSoup, and Pandas. The analysis covers various aspects, including extracting and analyzing genres, stars, ratings, and votes.

## File Descriptions

- `Web_Analysis_IMDB.ipynb`: This is the main Jupyter notebook file where all the data extraction, manipulation, and analysis happens.

## Project Overview

The project can be roughly divided into the following sections:

1. **Data Extraction**: The data is extracted from the HTML of IMDb movie pages using BeautifulSoup.

2. **Data Cleaning**: The extracted data is then cleaned and organized into a Pandas DataFrame for further analysis. This involves tasks like splitting comma-separated genres and stars into lists.

3. **Data Analysis**: Various analyses are performed on the cleaned data. For instance, we analyze the counts of different genres and stars, compute the correlation between ratings and votes, etc.

## Libraries Used

- BeautifulSoup
- pandas
- matplotlib

## How to Run

To run the notebook, you will need a Python environment with the above libraries installed. Then, you can simply open the notebook in Jupyter and run the cells.

Please note that the code in this notebook is meant to be a guide and might need modifications based on the actual HTML structure of the IMDb pages.

## Future Work

This is a simple project demonstrating web analysis of IMDb movies. There are numerous potential improvements and additions that could be made, such as:

- Analyzing more features (e.g., directors, reviews, etc.)
- Incorporating temporal trends (e.g., how have movie ratings or genres changed over the years?)
- Using more advanced text analysis techniques on movie descriptions or reviews

## Disclaimer

Please use this code responsibly and respect IMDb's terms of service and any scraping restrictions they may have.
