# HTML-data-scraping
### Full web-scraping and data analysis project
##### Module 11 Challenge: Web Scraping and Data Analysis

### OVERVIEW
In this project, I performed web scraping and data analysis on Mars-related data. The project consisted of two main deliverables:\

PART 1 : Scraping Titles and Preview Text from Mars News Articles: Extracting news article titles and preview text from the Mars News website.\

PART 2 : Scraping and Analyzing Mars Weather Data: Collecting and analyzing Mars weather data from an HTML table to uncover insights about Martian climate.


### REPOSITORY STRUCTURE
The repository is organized as follows:

```
mars-web-scraping/
│
├── part_1_mars_news.ipynb       # Jupyter Notebook for scraping Mars news articles
├── part_2_mars_weather.ipynb    # Jupyter Notebook for scraping and analyzing Mars 
├── mars_data.csv                # A CSV file containing mars data
├── README.md                    # Project documentation
└──license                 b     # Containing licence information for data usage
```
### TECHNOLOGIES USED
      1- Splinter: For automated browsing and interacting with web pages.\
      2- Beautiful Soup: For parsing HTML and extracting data.\
      3- Pandas: For data manipulation, analysis, and visualization.\
      4- Matplotlib: For creating visualizations.\
      5- Jupyter Notebook: For code execution and documentation.

### PROJECT STRUCTURE
### PART 1: Scraped Titles and Previewed Text from Mars News
- Automated Browsing: Used Splinter to visit the Mars News website and extract HTML content.
- HTML Parsing: Created a Beautiful Soup object to parse the HTML and extract news article titles and preview text.
- Data Storage: Stored each title and preview pair in a dictionary, with all dictionaries collected in a list.
- Output: Printed the list of dictionaries and optionally exported the data to a JSON file.

### Part 2: Scrape and Analyze Mars Weather Data
- Automated Browsing: Used Splinter to visit the Mars Temperature Data Site and extract the HTML table.
- HTML Parsing: Created a Beautiful Soup object to scrape the table data and assembled it into a Pandas DataFrame.
- Data Cleaning: Converted data types for columns (e.g., terrestrial_date to datetime, min_temp to float).

    ### DATA ANALYSIS\
    1- Determined the number of months on Mars.\
    2- Calculated the number of Martian days in the dataset.\
    3- Identified the coldest and warmest months on Mars.\
    4- Analyzed atmospheric pressure by month.\
    5- Estimated the duration of a Martian year in Earth days.\
    6- Data Visualization: Created bar charts to visualize temperature and pressure trends.\
    7- Data Export: Exported the cleaned DataFrame to a CSV file.

### KEY FINDINGS
PART 1 NEWS ARTICLES\
Successfully scraped and stored titles and preview text from Mars news articles.
Data was structured as a list of dictionaries for easy access and analysis.

PART 2 MARS WEATHER DATA\
1- Months on Mars: There are 12 months on Mars.\
2- The dataset contains data for 1867 Martian days.

3- TEMPERATURE TRENDS\
    The coldest month is Month 3 with an average minimum temperature of approximately -83°C.\
    The warmest month is Month 8 with an average minimum temperature of approximately -68 °C.

4- ATMOSPHERIC PRESSURE\
    The month with the lowest atmospheric pressure is Month 6 (average pressure: 745.05 Pa).
    The month with the highest atmospheric pressure is Month 9 (average pressure: 913.31 Pa).
    Martian Year: A Martian year is approximately 687 Earth days, based on the temperature cycle.

5- RESULTS\
    Mars News Data: A list of dictionaries containing titles and preview text was generated and optionally exported to JSON.
    Mars Weather Data: A cleaned and analyzed DataFrame was created, with visualizations and insights exported to a CSV file.

### ACKNOWLEGEMENTS
NASA Mars News Website: For providing the news articles and weather data.
edX Boot Camps: For the project instructions and resources.

LICENCE
This project is licensed under the GNU GENERAL PUBLIC LICENSE.
