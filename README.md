# household-power-analysis
Time-series analysis of household electricity consumption (2M+ records). Data cleaning, missing data handling, and usage pattern analysis (hourly and weekly trends).
# Household Power Consumption Analysis

## Goal
Analyze household electricity consumption data and identify usage patterns.

## Dataset
Time-series dataset with over 2 million records of household energy usage (2006–2010).

## Data Cleaning
- Combined Date and Time into a Datetime column
- Identified and removed incomplete measurement rows (~1.25%)
- Created a clean dataset for analysis

## Analysis
- Hourly consumption patterns
- Weekday vs weekend comparison
- Yearly trends

## Key Findings
- Peak consumption occurs in the evening (20:00–21:00)
- Lowest usage occurs overnight (03:00–05:00)
- Weekend consumption is higher than weekdays
- Missing data represents ~1.25% and was safely removed

## Tech Stack
- Python
- pandas
- matplotlib

## Notes
Dataset not included due to size.
