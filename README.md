# CIS_5367_HJMNS
Machine Learning Course 5367 Spring 2022 Project

Purpose:
  The purpose of this repository is to document the Machine Learning project for team C
  The project is focused on reviewing the data around average home sales/roi and census data to help users determine the best location (zip) and type of housing to         invest in.
  
To use the code you should first download the Redfin Housing Market Data 2012-2021 into your google drive. Shared Google Drive link provided 
Data is provided by  Kaggle.com
  Redfin Housing Market Data 2012-2021
  US housing market data 2012-2021 by different geographical region
  Use the below link to download the zip_code_market_tracker.tsv000
  https://www.kaggle.com/thuynyle/redfin-housing-market-data?select=zip_code_market_tracker.tsv000
# shared file location on google drive https://drive.google.com/file/d/1b-Z0Tt--ioLGhPTNwHVKyYY7mS7ynRJs/view?usp=sharing

  For using the exact line of code from repository to read the Refin data, after downloading the data set in the local computer from Kaggle
  You need to create a folder named "data" in the google drive and manually upload the data set in that "data" folder. or modify the file path in the correct read.csv(line

2nd Data Set from US Federal Census: American Community Survey
Code for requesting the API and read the data in the Getting Census Data File is in the Collab Notebook
currently the Census data only allows a pull from 1 year at a time, so the code iterates over the years (2012-2020) and populates a dataframe with the Zip Code and the assosiated Median Household Income by year. -66666666 is a null value in the census data

https://www.census.gov/programs-surveys/acs/data.html explains the data and allows viewing the records via web portal

Currently the project has some data initialization and manipulation to describe the data we are working with. 
