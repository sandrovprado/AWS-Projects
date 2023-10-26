# Los Angeles Crime Rate Analysis

## Overview

This project aims to analyze crime rate information in Los Angeles since 2020 using a government dataset. AWS services, such as S3 for data storage and Amazon QuickSight for data visualization, have been employed to perform this analysis. The goal is to gain insights into the most common crimes, plot crime occurrences on a map, and identify areas with the highest crime rates in Los Angeles.

## Data Source

The primary data source for this project is a government dataset containing crime data for Los Angeles since 2020.
https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

## AWS Services Utilized

1. **Amazon S3**: We used Amazon S3 as a data storage solution to store and manage the crime dataset efficiently.

2. **Amazon QuickSight**: Amazon QuickSight was employed for data visualization and to create informative visualizations based on the provided CSV data.

## Visualizations Created

1. **Most Common Crimes Donut Chart**: A donut chart has been generated to illustrate the most common types of crimes in Los Angeles. This visualization provides a quick overview of the prevalent crime categories.<img width="1342" alt="Screen Shot 2023-10-26 at 12 31 51 PM" src="https://github.com/sandrovprado/AWS-Projects/assets/53231989/ab07e583-bdfe-42bb-98cb-d64bcac71944">


2. **Crime Occurrence Map**: This visual takes the latitude and longitude of each crime site and plots them on a map. It provides a geographic representation of the types of crimes that have occurred at different coordinates within Los Angeles.<img width="1342" alt="Screen Shot 2023-10-26 at 12 25 58 PM" src="https://github.com/sandrovprado/AWS-Projects/assets/53231989/6c8d153e-e10d-42ef-aaae-aa4ac9e004bb">


3. **Highest Crime Rate Areas Bar Chart**: This visualization displays the areas in Los Angeles with the highest crime rates. It associates the area names with the respective crime counts and arranges them in descending order of crime rates. This chart helps in identifying areas that need increased attention regarding crime prevention and law enforcement.<img width="1342" alt="Screen Shot 2023-10-26 at 12 32 39 PM" src="https://github.com/sandrovprado/AWS-Projects/assets/53231989/dcff3277-8514-49da-b971-a489b04d04c2">


## Conclusion

This project combines the power of AWS services with government data to gain insights into crime rates in Los Angeles since 2020. The visualizations created provide valuable information for understanding the distribution of crime types and identifying areas with the highest crime rates. This information can be useful for law enforcement agencies and policymakers to make informed decisions and take necessary actions to improve public safety in Los Angeles.

