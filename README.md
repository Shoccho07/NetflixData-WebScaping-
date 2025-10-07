Netflix Stock Data Web Scraping
Project Overview

This project demonstrates how to extract historical stock price data for Netflix from a webpage using Python. The data includes:

Date

Open price

High price

Low price

Close price

Adjusted Close price

Volume

We use Beautiful Soup to parse the HTML and pandas to store the data in a structured format. The resulting DataFrame can be used for analysis, visualization, or further financial studies.

Technologies Used

Python 3.x

pandas

Beautiful Soup (bs4)

requests

How It Works

Load the webpage containing the Netflix stock table.

Parse the HTML with Beautiful Soup.

Loop through each row in the table body (<tbody>).

Extract data from each column (<td>) in the row.

Store each row in a pandas DataFrame.
