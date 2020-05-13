Project 5: Predicting the Economic Impact of Natural Disasters :ocean:

---
## Project Authors:

Victor Voskovsy  - [LinkedIn](https://www.linkedin.com/in/victorvoskovsky) <br>
Bryan Lange  - [LinkedIn](https://www.linkedin.com/in/bryanrobertlange) <br>
Andrew Davis  

---
## Executive Summary

### Problem Statement

According to the NOAA, since 1980 the United States has experienced 265 weather and climate disasters where the overall costs reached or exceeded one billion dollars. The ability to predict potential wage loss from natural disasters will help communities focus their rebuilding efforts on the industries that need it most and help to mitigate economic impact. Using major hurricane data combined with data from the Bureau of Labor Statistics, our goal is to provide an estimation about the projected economic loss in a given locality based on the reported or estimated wage loss in that region after a natural disaster.  

---
## Data Information

| Data Source | Description | Link |
| --- | --- | --- |
| U.S. Bureau of Labor Statistics (BLS) | The Quarterly Census of Employment and Wages (QCEW) | [Link](https://www.bls.gov/cew/about-data/data-files-guide.htm)|
| NOAA | Location, wind, and pressure of tropical cyclones in Atlantic and Pacific Oceans | [Link](https://www.kaggle.com/noaa/hurricane-database)|

---

#### BLS Quarterly Employment Data
- Used Google BigQuery and SQL to pull quarterly employment data stretching back 30 years to help compare wage and unemployment rates during natural disasters 
    - Monthly emplyoment levels by industry, average weekly wages and over-the-year percent change data was pulled using BigQuery

#### NOAA hurricane data 
- Used CSV file provided by The National Hurricane Center (NHC) to determine hurricane category
    - These databases (Atlantic HURDAT2 and NE/NC Pacific HURDAT2) contain six-hourly information on the location, maximum winds, central pressure, and (starting in 2004) size of all known tropical cyclones and subtropical cyclones.  

---
### Data Preprocessing and EDA


### Key Findings


### Obstacles and recommendation


### Conclusion
