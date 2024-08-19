# Covid19-Data- Insights 
## Table of Contents
- Project Overview
- Data Sources
- Tools
- Data Cleaning/Preparation
- Exploratory Data Analysis
- Data Analysis
- Data Visualizations
- Results and Findings
- Limitations
- References

## Project Overview 
This project aims to conduct a comprehensive data analysis of COVID-19, focusing on the dynamics of cases, deaths, infections, and vaccination rates across various countries and continents from 2019 to 2021. The study will investigate how these key metrics evolved, exploring regional and global trends to discern patterns and insights that can inform public health strategies and policies.

## Data Sources
The data for this analysis was sourced from https://ourworldindata.org and is contained within the covid_19.csv file. This dataset provides detailed information on deaths, cases, vaccinations, and age groups across various countries and continents from 2019 to 2021. The data was later divided into two datasets; Covid vaccinations and deaths.

## Tools 
- Excel Data Cleaning.
- MySql Server - Data analysis.
- Tableau - Creating Reports and Visualizations.

## Data Cleaning/Preparation
In the initial data preparation phase, we undertook several key tasks to ensure the dataset was ready for analysis:
1. Data Loading and Inspection: We began by importing the dataset from the covid_19.csv file and performing an initial review to understand its structure and contents. To facilitate a more detailed examination, the file was divided into two separate files: covid_vaccination and covid_death. This separation allowed us to focus individually on vaccination and death case data.

2. Handling Missing Values: We identified and addressed any missing or incomplete entries within both the covid_vaccination and covid_death files. This process included determining the best approach to impute or manage these gaps, ensuring that the analysis remained accurate and comprehensive.

3. Data Cleaning and Formatting: We refined both datasets by correcting inconsistencies and errors. This involved standardizing formats, resolving discrepancies, and ensuring that the data was organized and formatted correctly for subsequent analysis. This step was crucial for obtaining reliable and actionable insights. Finally, the datasets were uploaded to MySql for further data exploration and analysis.

## Exploratory Data Analysis
EDA involved exploring the Covid-19 data to answer some key questions such as:
- What is the vaccination rate per country?
- How do total cases compare to total deaths across continents?
- What is the mortality rate analysis for each continent?
- What are the global totals for deaths, vaccinations, population, and cases?
- Which countries have the highest infection rates compared to their population?
- Which countries have the highest death counts per population?
- What percentage of the population has received at least one COVID-19 vaccine?

A view was specifically created to provide a clear and interactive visualization of our data, allowing for more intuitive analysis and better insight into the patterns and trends within the dataset.


## Data Analysis
Here are some examples of SQL queries that were executed to support our analysis:

1. Query for Vaccination Rate per Country: This SQL code retrieves and calculates the vaccination rates for each country, providing insights into how different nations are progressing with their vaccination efforts.

2. Query for Total Cases vs. Total Deaths per Continent: This query compares the total number of COVID-19 cases to the total number of deaths across various continents, helping to assess the impact of the virus on different regions.

3. Query for Mortality Rate Analysis per Continent: This SQL command calculates and analyzes the mortality rates for each continent, offering a perspective on the severity of the pandemic in different parts of the world.

4. Query for Global Numbers: This query aggregates global statistics, including total deaths, total vaccinations, total population, and total cases, providing a comprehensive overview of the pandemic's impact on a worldwide scale.

Here is the attached file containing all the SQL code that was executed for the analysis. This document includes the specific queries used to extract, manipulate, and visualize the data, providing a detailed overview of the steps taken to analyze the dataset.

## Results and Findings
The analysis results are summarized as follows:
- 

## Data Visualization

## Limitation
The dataset contains a significant number of null values and missing data, which poses a challenge to the accuracy and reliability of the analysis. These gaps can lead to incomplete or skewed insights, as crucial information regarding cases, deaths, and vaccinations may be absent or underrepresented. Consequently, any conclusions drawn may not fully reflect the true scope of the pandemic or its impact. The presence of missing data also complicates efforts to perform precise statistical analyses and could affect the robustness of trend evaluations and comparisons across different regions.
