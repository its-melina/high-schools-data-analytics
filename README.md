# Santa Clara County High Schools: Relationship between Demographic Data and Graduation Rates

The goal of this project is to analyze demographic data of high schools in Santa Clara County and determine the demographic variables, if any, which best predict graduation rate of a school in the county. Future data analysis could include analyzing factors outside of demographic data, as well as expanding the analysis to include all schools in the state or comparing results with different counties.

## Outline 

### `data_scraping.ipynb`

1. Initial Data Scraping
    * Employs python's Beautiful Soup library to extract school demographic data
2. Data Cleaning
    * Cleans the DataFrame object containing web-scraped data
3. Exploratory Data Analysis
    * Analyzes relationships between quantitative continuous demographic variables 
4. Data Scraping of Graduation Rates
    * Employs python's Selenium library to dynamically scrape graduation rate data from multiple webpages by school district name
5. Exporting Data for Analysis
    * Exports data to a CSV file to avoid repetitive scraping for analysis purposes

### `grad_rate_analysis.ipynb`


