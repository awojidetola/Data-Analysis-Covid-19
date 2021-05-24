
# NIGERIA COVID 19 DATA ANALYSIS USING PYTHON

## Overview of the Project
The project is used to analyze the impact of Covid 19 on Nigerian States. The most affected states and the effect of the pandemic on the Gross Domestic Product (GDP) of the country.

## Data Preparation
Step 1: Importing Useful Libraries
The following Libraries were used in this project:
* Urllib, Request, Beautiful Soup, csv for Web Scraping
* Numpy for Numerical Analysis
* Pandas for Reading, Cleaning and Analysing data
* Matplotlib and Seaborn for visualization
* Warnings

### Step 1: Extracting the Dataset
* The NCDC data was Scraped from https://covid19.ncdc.gov.ng/  website using Urllib, Requests, Beautiful Soup Packages. The extracted data was saved in a .csv format for futher use
* Recovery, Death and Confirmed Cases at the Global level were extracted from the John Hopkins Repository
* External Datasets: covid_external, Budget data, RealGDP were loaded

### Step 2: Viewing the Data
Each of the datasets were loaded into pandas datafrmaes and viewed  using the .head() and .info() methods

### Step 3: Cleaning the Data
Unnecessary characters such as comma and trailing spaces were removed from the Scraped NCDC dataset
The data types of the dataset were converted from string type to integer type as appropriate

## Analysis
* Nigeria dadta was extracted from the Global dataset
* Visualizations were done on the Confirmed, Recovered and Death Cases of the NCDC dataset using Bar Chart and Line Plot
* The maximum infection rate for a day in Nigeria was gotten from the Global Dataset
* The relationship between the Lab Confirmed Cases and Population Density was visualized using Seaborn's Regplot
* The GDP for Seven years was visualized to check the effect on Covid 19 on the GDP
* The effect of the National Budget for each state was visualized and the Initial Budget (before the Pandemic) was compared to the Revised (After the Pandemic)
