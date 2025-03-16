# HTML-data-scraping
full web-scraping and data analysis project

Module 11 Challenge: Web Scraping and Data Analysis
Overview
In this project, I performed web scraping and data analysis on Mars-related data. The project consisted of two main deliverables:

Scraping Titles and Preview Text from Mars News Articles: Extracting news article titles and preview text from the Mars News website.

Scraping and Analyzing Mars Weather Data: Collecting and analyzing Mars weather data from an HTML table to uncover insights about Martian climate.

The project utilized Splinter for automated browsing, Beautiful Soup for HTML parsing, and Pandas for data manipulation and analysis.

Repository Structure
The repository is organized as follows:

Copy
mars-web-scraping/
│
├── part_1_mars_news.ipynb       # Jupyter Notebook for scraping Mars news articles
├── part_2_mars_weather.ipynb    # Jupyter Notebook for scraping and analyzing Mars weather data
└── README.md                    # Project documentation
Project Breakdown
Part 1: Scrape Titles and Preview Text from Mars News
Automated Browsing: Used Splinter to visit the Mars News website and extract HTML content.

HTML Parsing: Created a Beautiful Soup object to parse the HTML and extract news article titles and preview text.

Data Storage: Stored each title and preview pair in a dictionary, with all dictionaries collected in a list.

Output: Printed the list of dictionaries and optionally exported the data to a JSON file.

Part 2: Scrape and Analyze Mars Weather Data
Automated Browsing: Used Splinter to visit the Mars Temperature Data Site and extract the HTML table.

HTML Parsing: Created a Beautiful Soup object to scrape the table data and assembled it into a Pandas DataFrame.

Data Cleaning: Converted data types for columns (e.g., terrestrial_date to datetime, min_temp to float).

Data Analysis:

Determined the number of months on Mars.

Calculated the number of Martian days in the dataset.

Identified the coldest and warmest months on Mars.

Analyzed atmospheric pressure by month.

Estimated the duration of a Martian year in Earth days.

Data Visualization: Created bar charts to visualize temperature and pressure trends.

Data Export: Exported the cleaned DataFrame to a CSV file.

Technologies Used
Splinter: For automated browsing and interacting with web pages.

Beautiful Soup: For parsing HTML and extracting data.

Pandas: For data manipulation, analysis, and visualization.

Matplotlib: For creating visualizations.

Jupyter Notebook: For code execution and documentation.

Key Findings
Mars News Articles:

Successfully scraped and stored titles and preview text from Mars news articles.

Data was structured as a list of dictionaries for easy access and analysis.

Mars Weather Data:

Months on Mars: There are 12 months on Mars.

Martian Days: The dataset contains data for 1867 Martian days.

Temperature Trends:

The coldest month is Month 3 with an average minimum temperature of approximately -83.31°C.

The warmest month is Month 8 with an average minimum temperature of approximately -68.38°C.

Atmospheric Pressure:

The month with the lowest atmospheric pressure is Month 6 (average pressure: 745.05 Pa).

The month with the highest atmospheric pressure is Month 9 (average pressure: 913.31 Pa).

Martian Year: A Martian year is approximately 687 Earth days, based on the temperature cycle.

Results
Mars News Data: A list of dictionaries containing titles and preview text was generated and optionally exported to JSON.

Mars Weather Data: A cleaned and analyzed DataFrame was created, with visualizations and insights exported to a CSV file.

Installation and Setup
Clone this repository to your local machine.

Install the required libraries using pip install splinter beautifulsoup4 pandas matplotlib.

Open the Jupyter Notebooks (part_1_mars_news.ipynb and part_2_mars_weather.ipynb) to execute the code and perform the analysis.

Acknowledgements
NASA Mars News Website: For providing the news articles and weather data.

edX Boot Camps: For the project instructions and resources.

License
This project is licensed under the GNU GENERAL PUBLIC LICENSE.
