# UFO-Sightings-around-the-world
  
## Introduction
This project was completed using Power BI. 
It is a report showing information of UFO Sightings from around the world. The Dataset is from Kaggle. I have created a report with 3 tabs so different pieces of information can be easily seen.

## About the Dataset
The dataset was downloaded from Kaggle.
There was a lot of cleaning of data in the City Names as the characters were not showing correctly making the city name look stranges. The name contained unicode character names and codes which did not show so I had to search for the name and paste the correct character in to replace the incorrect details. I may not have replaced all of them as this took a long time to complete. Also I had to fix problems in the comments this was to help with the sighting description word cloud. I also had to fix errors with states having the country as N/A i was able to set the country to US. 
There is work still to be done on cleaning the city names as sometimes the city has the country name in brackets but nothing in the 2 character country code column. There are also US States where the country code is set to N/K and the same of other cities from other countries where the country is in the city description but the country is set to N/K. I have completed several of these but have not completed it.
Another way to clean this data is to write a Python application that reads the csv file and performs the cleaning steps that are currently performed using power query in Power BI and outputs a clean file for Power BI to read the only drawback to this approach this is not an automatic approach. A final option is to use Python code in the power query editor to perform the data cleaning this would automate the process but would be of use to people who are better at Python than Power Query.
