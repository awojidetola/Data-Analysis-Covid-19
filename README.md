
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

# Visualizing the COVID 19 Pandemic using Tableau

# Visualizing-the-COVID-19-Pandemic

**Please find these visuals in Tableau Public here:** https://public.tableau.com/app/profile/margaret.awojide/viz/Book1_16341217339570/Story1

This project gives a visual explanation of the Covid 19 Pandemic for all countries of the World, analyzing each country and the Confirmed Cases, Recovered Cases and Death Cases. 

## Visual 1
The first visual shows the Death Statistics for Covid 19 in 2020. With United States having the highest number of Death Cases followed by Brazil and India. 

## Visual 2
The second visual shows the Confirmed Cases and Death Cases in all countries of the World. Here, the size increases with an increased number of Confirmed cases and the color intensifies with an increased number of Death Cases.

## Visual 3
The third visual shows the line plot comparing the three most affected countries and how confirmed cases increased over time in 2020. 

## Visual 4
The fourth visual shows the line plot comparing the Confirmed, Recovered and Death Cases, clearly depicting that Recovery rate was higher than the Death rate. 

![Visual1_2](https://user-images.githubusercontent.com/49078266/137206086-12bb023d-5936-4412-ab96-9853881917f5.png)
![Visual3_4](https://user-images.githubusercontent.com/49078266/137206118-f5a1d0a1-e5cd-4e5a-8e7b-116a94f5cef7.png)

