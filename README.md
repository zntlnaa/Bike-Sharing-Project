# Analysis of Bike Sharing Rental Trends during 2011-2012

This project analyzes the bike-sharing rental trends during the period of 2011-2012. The goal is to identify patterns in bike rentals, considering factors like seasonality, weather conditions, and holidays, which influence the demand for bike rentals.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Conclusion](#conclusion)

## Project Overview
This project analyzes bike rental trends from the Bike Sharing dataset. By examining rental counts across months and different conditions, it aims to uncover insights into how demand fluctuated during 2011-2012. This analysis helps in understanding patterns and planning improvements for bike-sharing systems.

## Data Sources
- **Bike Sharing Dataset**: The Bike Sharing Dataset contains data regarding bike rentals in a bike-sharing system. This dataset includes information about the number of bikes rented each hour and factors influencing rental numbers, such as weather, holidays, seasons, temperature, humidity, and wind speed. The data can be used to analyze bike rental patterns and identify factors affecting the demand for bikes, which can help enhance the management and performance of the bike-sharing system.

## Methodology
### 1. Defining Questions
The first step in the data analysis process is to define various analysis questions related to the data or the problem to be solved. These questions will help understand the business problem at hand and the goals to be achieved.

### 2. Data Wrangling
- **Gathering Data**: The dataset used is the Bike Sharing Dataset (from Kaggle).
- **Assessing Data**: Identifying various issues in the data such as missing values, duplicates, incorrect data types, etc.
- **Cleaning Data**: Cleaning the data based on the issues identified, such as fixing incorrect data types.

### 3. Exploratory Data Analysis (EDA)
- View the statistical summary of the data (`day_df` and `hour_df`).
- Analyze bike rental counts by month across 2011-2012.
- Analyze the number of bike rentals by registered users and casual users during 2011-2012.
- Examine daily rental statistics for registered and casual users during 2011-2012.
- Investigate bike rental distribution by season during 2011-2012.
- Analyze bike rental distribution by weather condition during 2011-2012.
- Analyze bike rentals on working days during 2011-2012, and more.

### 4. Data Visualization
- Data is presented in visual formats to facilitate understanding.
- Trends in the data are shown using line charts.
- The distribution of categorical data is illustrated using bar charts.

### 5. Conclusion & Communication
- Based on the data analysis, there was an increase in the number of bike rentals from January to June, both in 2011 and 2012. Conversely, from September to December, a tendency for a decrease in rentals is observed in both years.
- The number of bike rentals tended to be lower during the spring season compared to other seasons, and higher during the fall season, both in 2011 and 2012.

## Results
- The data analysis indicates an increase in the number of bike rentals from January to June, both in 2011 and 2012. However, from September to December, a decline in rentals is observed in both years.
- Additionally, bike rentals were lower during the spring season compared to other seasons in both 2011 and 2012, whereas they were higher during the fall season.

## Conclusion
- Based on the data analysis process, there was an increase in bike rentals from January to June, both in 2011 and 2012. Conversely, from September to December, there was a tendency for a decrease in rentals, both in 2011 and 2012.
- The number of bike rentals was lower during the spring season compared to other seasons, and higher during the fall season, in both 2011 and 2012.

## Tools & Libraries
- Pandas
- Numpy
- Babel
- Matplotlib
- Streamlit
- Visual Studio Code
