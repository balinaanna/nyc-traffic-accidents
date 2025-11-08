# NYC Traffic Accidents (Jan–Aug 2020)

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?logo=microsoftexcel&logoColor=white)

An exploratory data analysis of motor vehicle collisions reported by the New York City Police Department (NYPD) between January and August 2020.  
This project focuses on identifying monthly trends, temporal patterns, high-risk locations, and common contributing factors.

## Dataset

**Source**: [NYC OpenData](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95) - Motor Vehicle Collisions  
**Format**: CSV
**Rows:** 74,881
**Columns:** 29
**Time Period:** January - August 2020  
**Features include:** date/time, location (borough, zip code, lat/lon), street names, vehicles involved, injuries/fatalities, contributing factors

## Tools used
- **Microsoft Excel for Web** - data cleaning, transformation, and visualization  
- **Pivot Tables & Charts** - aggregations and comparisons  
- **Conditional Formatting** - heatmap visualizations  
- **GitHub** - portfolio presentation

## Data Cleaning & Preparation
1. Used `=ROWS()` and `=COLUMNS()` to check dataset size.
2. Used `Filter` to identify and `=COUNTBLANK()` to measure missing values.
3. Removed columns with 90%+ missing values (Vehicle Type 3–5, Contributing factor 3-5).
4. Standardized column formats:
  - Dates → `Date` format
  - Times → `Time` format
  - ZIP codes, IDs → `Text`
  - Lat/Lon → `Number (6 decimals)`
  - Number of kills/injures  → `Number (no decimals)`.
5. Created **helper columns**:
  - Month, Month Name, Day of Week, Is Fatal (True/False) : `Text`
  - Hour: `Number`
6. Verified completeness and ensured date range: January – August 2020.
