# NYPD Shooting Incidents
This is the first of two projects developed for the course *Data Science as a Field* (DTSA-5301) at University of Colorado Boulder.

## Description
The project presents an in-depth analysis of shooting incidents in New York City from 2006 to 2022, examing temporal and spatial patterns of gun violence.

## Data Source
The data is provided by the City of New York and can be accessed at [NYPD Shooting Incident Data (Historic)](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data).

## Key Features:
* **Data Preprocessing**: Cleans and structures the dataset to facilitate accurate analysis, including handling missing values and ensuring consistency in data formats.
* **Temporal Analysis**: Examines shooting incidents over time to identify trends, seasonal patterns, and anomalies.
* **Spatial Analysis**: Compares shooting incidents per capita in New York's five boroughs.

## Results (Summary)

### Long-term trend
The number of shooting incidents trended down from 2006 to 2019, but jumped back up in 2020.

<img src="https://github.com/user-attachments/assets/e273a722-d135-4acc-a461-19fa5f594053" alt = "Shootings in New York City 2006-2022" width = "500">

### Distribution throughout the day
Shootings are most frequent between 11 p.m. and 2 a.m. and lest frequent between 6 a.m. and 11 a.m. The difference is huge.

<img src="https://github.com/user-attachments/assets/d349d0e0-5cd4-4a0b-9f55-74a73b38dcf1" alt = "Shootings per hour of the day" width = "500">

### Distribution throughout the yar
Shootings are most frequent during the summer and least frequent in the winter.

<img src="https://github.com/user-attachments/assets/026a566c-13af-4ee8-a45b-9537ef5f5e9c" alt = "Shootings per month" width = "500">

### Increase in shootings 2020
In 2020, the first year of the pandemic, there was a large increase in shootings compared with 2018 and 2019, but the increase is not perfectly correlated with the start of the COVID lockdowns, which in New York City began around March 17, 2020. Rather, March and April of 2020 saw numbers similar to the corresponding months in 2018 and 2019; May shows a sharp increase, while the largest difference came in July and August, which had almost three times as many shootings as the same months in 2018 and 2019.

<img src="https://github.com/user-attachments/assets/ff3d8530-8ffe-4e3b-b0d5-09c43a215c0a" alt = "Shootings per month, 2018-2021" width = "500">

### Differences among the boroughs
The Bronx was the borough with the highest number of shootings per million inhabitants, and Staten Island the one with the lowest. This comparison does not take into consideration that Manhattan has a much larger number of daily visitors than the other boroughs.

<img src="https://github.com/user-attachments/assets/70eddfab-343f-4279-a56a-75fef1888fc9" alt = "Shootings per million inhabitants" width = "500">

## Repository Content
* [Report in HTML format](https://olaklingberg.github.io/NYPD-Shooting-Study/NYPD_Shootings.html)
* [RStudio file](https://github.com/OlaKlingberg/NYPD-Shooting-Study/blob/main/NYPD_Shootings.Rmd)
