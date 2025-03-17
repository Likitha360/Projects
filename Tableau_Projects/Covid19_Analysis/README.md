# COVID-19 Data Analysis Tableau Workbook

## Overview
This Tableau workbook analyzes COVID-19 data from the covid_19_clean_complete.csv dataset. It includes visualizations to explore confirmed cases, deaths, recoveries, and active cases across various countries and regions, with data extracted as of March 4, 2025. The workbook was created using Tableau version 18.1 (build 20243.24.1010.1014) on a Windows platform.

## Dataset
#### Source
  File: covid_19_clean_complete.csv
  Format: CSV (comma-separated, UTF-8 encoding, with headers)
  Extract: A Tableau Hyper extract is stored at the location of your tablue workbooks.

#### Columns
The dataset includes the following columns:
- Province/State (String): Province or state within a country.
- Country/Region (String): Country or region name.
- Lat (Real): Latitude coordinate.
- Long (Real): Longitude coordinate.
- Date (Date): Date of the record.
- Confirmed (Integer): Number of confirmed COVID-19 cases.
- Deaths (Integer): Number of deaths due to COVID-19.
- Recovered (Integer): Number of recovered cases.
- Active (Integer): Number of active cases.
- WHO Region (String): World Health Organization region.

#### Data Notes
The data contains null values in some columns (e.g., Province/State, Lat, Long).
The extract was last updated on March 4, 2025, at 10:47:44 AM.

## Visualizations
The workbook contains the following sheets:

#### Bar Chart
Title: "Total Confirmed Cases by Country (July 27, 2020)"
Description: Displays the total confirmed COVID-19 cases for selected countries as of July 27, 2020.
Filter: Includes specific countries such as Australia, China, France, India, Italy, Japan, Pakistan, Russia, South Africa, and the US.

#### KPI Table
Description: Likely a summary table showing key performance indicators (e.g., total confirmed, deaths, recovered, active cases). Exact details are not fully specified in the XML.

#### Line Chart
Description: Likely shows trends over time (e.g., confirmed cases by date). Specific details are truncated in the XML.

## Color Coding
The Country/Region dimension uses a custom color palette in the Bar Chart, with colors assigned to specific countries (e.g., #4e79a7 for Angola, Brazil, Pakistan; #76b7b2 for India).

## Prerequisites
Software: Tableau Desktop (version 18.1 or compatible)
Operating System: Windows
Dataset: Ensure covid_19_clean_complete.csv is available at the specified path or update the data source connection if moved.

## License
This project is for educational purposes and uses publicly available COVID-19 data. Ensure compliance with any data usage terms from the original source.

