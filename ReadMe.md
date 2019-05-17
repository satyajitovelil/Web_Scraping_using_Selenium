# Dynamic Web Scraping

## The python code uses the Selenium and Beautifulsoup modules to scrape climate data from www.indiawaterportal.com

### The data available on the aforementioned website is available in a table format for a particular variable/parameter for a given year (selected using a form). The form updates dynamically after changing states to include the respective districts.

#### As of now the script needs two things:
1. A function that takes the variable and the duration (from-year and to-year) as arguments.
2. Removal of redundant wait conditions.