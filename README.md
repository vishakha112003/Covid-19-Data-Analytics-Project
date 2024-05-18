# Covid-19-Data-Analytics-Project

## Overview
The COVID-19 Analytics Project is designed to gather, analyze, and visualize data related to the COVID-19 pandemic. This project aims to provide insights into the spread of the virus, the effectiveness of interventions, and the impact on various demographics.
## Table of Contents
- Data Collection
- Data Cleaning
- Exploratory Data Analysis
- Power BI Dashboard
## Data Collection
The dataset was downloaded from the WHO official website. The data has records from the day the pandemic started till March 2024. The dataset contains data about daily new cases and deaths, vaccinations, tests and many otther columns related to the covid-19 pandemic.
## Data Cleaning
Data cleaning involved:
- dropping unnecessary columns
- dropping null values from the column continent
- filling in the missing values for the age groups with the median value of their respective column
- removing columns with more than 50% missing values
- filling missing values in the column stringency index with 0
- filling the null values in median age with previous values
- Changing the format of date
The cleaned data was then saved into a new file.
## Exploratory Data Analysis
First, the preliminary examination of data was done to understand what the data says. Then some new features like month, week, weekday etc. were created using the data column for use in the analysis.
Data was visualized through matplotlib and seaborn to understand the trends and gather insights from the data at the end.
![]/images/EDa.png



