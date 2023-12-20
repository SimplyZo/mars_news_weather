# Part 1 Mars News
The notebook scrapes article titels and preview text from a Mars news website using Splinter and BeautifulSoup

It contains the following sections

### Imports
Import Splinter for automated browsing and BeautifulSoup for web scraping

### Visit Website
Uses Splinter to automatically visit the Mars news website.

### Scrape with BeautifulSoup
Creates a BeautifulSoup object to parse the website HTML. Finds all div elements with the list_text class which contain the news articles.

### Store in Python Data Structures
Loops through the elements and extracts the title and preview text for each article. Stores each pair in a Python dictionary with 'title' and 'preview' keys. Adds each dictionary to a Python list called news_list.

### Print Results
Prints the news_list to confirm the titles and previews were successfully scraped.

# Part 2 Mars Weather

This notebook scrapes Mars weather data from a table on a website and analyzes the data.

It contains the following key sections:

### Imports and Setup
Imports libraries including Pandas, BeautifulSoup, matplotlib, and splinter. Initializes a splinter browser. 

### Scrape Mars Weather Table
Visits the Mars weather data URL. Uses BeautifulSoup to find the table and extract all the rows.

### Store in DataFrame
Stores the scraped data in a Pandas DataFrame for analysis. Prints the DataFrame to confirm.

### Data Analysis
Asks and answers 5 key questions about the Mars weather using DataFrame operations:

1. How many months of data exist?
2. How many terrestrial days of data? 
3. Average low temp per month?
4. Average pressure per month?
5. How many earth days per Mars year?

Also creates plots to visualize the temperature and pressure by month.

### Export CSV
Exports the DataFrame to a CSV file.
