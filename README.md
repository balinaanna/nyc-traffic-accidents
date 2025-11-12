# NYC Traffic Accidents (Jan-Aug 2020)

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?logo=microsoftexcel&logoColor=white)

The project was developed to practice end-to-end data analysis using real-world open data.  
It applies Excel-based analytics to identify trends, patterns, and potential risk factors in NYC motor vehicle collisions reported  between January and August 2020.


## Skills Demonstrated
- **Data cleaning and wrangling** in Excel (formatting, handling missing values).  
- Feature engineering using **formulas** and **helper columns**.  
- Aggregation and analysis with **Pivot Tables** and **conditional formatting**.  
- **Visualization** with combo charts, bar charts, and heatmaps.  
- Analytical storytelling and insight communication through data.  

## Dataset

**Source**: [NYC OpenData](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95) - Motor Vehicle Collisions  
**Format**: CSV  
**Rows:** 74,881  
**Columns:** 29  
**Time Period:** January - August 2020  
**Features include:** date/time, location (borough, zip code, lat/lon), street names, vehicles involved, injuries/fatalities, contributing factors

## Data Cleaning & Preparation
1. Used `=ROWS()` and `=COLUMNS()` to check dataset size.
2. Used `Filter` to identify and `=COUNTBLANK()` to measure missing values.
3. Removed columns with 90%+ missing values (Vehicle Type 3–5, Contributing factor 3-5).
4. Standardized column formats:
  - Dates → `Date` format
  - Times → `Time` format
  - Borough, ZIP codes, street names, collision IDs, contributing factors, vehicle types → `Text`
  - Lat/Lon → `Number (6 decimals)`
  - Number of kills/injures  → `Number (no decimals)`.
5. Created **helper columns**:
  - Month, Month Name, Day of Week, Is Fatal (True/False) : `Text`
  - Hour: `Number`
6. Verified completeness and ensured date range: January – August 2020.

## Analysis & Insights

### 1. Monthly Trends

### 2. Day-Hour Patterns

### 3. High-Rist Locations

### 4. Contributing factors


