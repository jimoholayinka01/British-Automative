# British-Automative
This project focuses on web scraping, data cleaning, and exploratory data analysis (EDA) of automotive market data in the UK. The goal is to extract insights into consumer trends, pricing, and popular vehicle models from multiple sources. The final dataset is stored in a structured format for further analysis.
# Web Scraping and Exploratory Data Analysis (EDA) in R

## Project Overview
This repository contains the scripts and outputs for a web scraping and data analysis project focused on the British automotive industry. The project involves gathering data from multiple automotive websites, cleaning the data, and performing exploratory data analysis (EDA) to identify trends and insights. The data was scrapped from these three british automotive inudstry.
1. https://www.thecarco.co.uk/
2. https://www.autotrader.co.uk/
3. https://www.motorpoint.co.uk/

## Objectives
1. **Data Collection**: Use at least two web scraping tools/packages to extract relevant automotive data.
2. **Data Cleaning**: Process and structure the data to ensure consistency and usability.
3. **Exploratory Data Analysis (EDA)**: Analyze the cleaned data using summary statistics and visualizations.

## Technologies Used
- **R** (RStudio for development)
- **rvest**: Web scraping package
- **RSelenium**: For dynamic website interaction
- **tidyverse**: Data cleaning and transformation
- **ggplot2**: Visualization

  ## How to use
  **The Main Script is present in British Automative Script.rmd**
**Update the Website URL (if needed)**
- The web scraping scripts use a variable named url to define the target website. If the website link changes, update the url variable in the Rmd script.
- The Rmarkdown contains all the steps from the scrapping, cleaning and EDA process splitted with each code chunk and comments.

## Results & Findings
- Summary statistics reveal trends in pricing, popular models, and consumer interest.
- Visualizations highlight key patterns and outliers in the dataset.
- The cleaned dataset is structured and ready for further analysis in the car_data_file.csv

## Future Work
This project focuses on data collection, cleaning, and initial analysis. Further work may include:
- Predictive modeling to forecast price trends.
- Sentiment analysis on consumer reviews.
- Enhanced feature engineering for deeper insights.


