# Advanced Database Topics - Semester Project

## Overview
This repository contains the implementation of the semester project for the course **Advanced Database Topics** at **NTUA ECE**. The project involves analyzing large datasets using **Apache Spark** and **Apache Hadoop** on **AWS S3** and **SageMaker**.

## Data
The datasets used in this project are publicly available and hosted on **AWS S3**:

| Dataset Description                | Format | S3 URI                                                                                     |
|------------------------------------|--------|--------------------------------------------------------------------------------------------|
| Los Angeles Crime Data (2010-2019) | CSV    | `s3://initial-notebook-data-bucket-dblab-905418150721/CrimeData/Crime_Data_from_2010_to_2019_20241101.csv` |
| Los Angeles Crime Data (2020-)     | CSV    | `s3://initial-notebook-data-bucket-dblab-905418150721/CrimeData/Crime_Data_from_2020_to_Present_20241101.csv` |
| LA Police Stations                 | CSV    | `s3://initial-notebook-data-bucket-dblab-905418150721/LA_Police_Stations.csv`              |
| Median Household Income by Zip Code| CSV    | `s3://initial-notebook-data-bucket-dblab-905418150721/LA_income_2015.csv`                 |
| 2010 Census Blocks                 | GeoJSON| `s3://initial-notebook-data-bucket-dblab-905418150721/2010_Census_Blocks.geojson`         |
| Race and Ethnicity Codes           | CSV    | `s3://initial-notebook-data-bucket-dblab-905418150721/RE_codes.csv`                       |

## Queries
1. **Query 1:** Categorize and sort victim age groups involved in aggravated assault cases.
2. **Query 2:** Identify the top 3 police stations by closed case rate for each year.
3. **Query 3:** Compute per capita income and crime ratios for each region.
4. **Query 4:** Analyze the racial profile of crime victims in regions with the highest/lowest income.
5. **Query 5:** Compute the crime count and average distance to the closest police station for each division.
