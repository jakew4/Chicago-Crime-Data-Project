# Chicago Crime Data Project

![chicago police](https://user-images.githubusercontent.com/112730629/219494357-cb7891a2-b424-4364-bc92-1a074e8d4064.jpeg)

* Author: Jacob Wang
* Created: February 16, 2023
* Last updated: March 6, 2023

# Business Problem: Analyze crime data and answer important questions about crime in Chicago.

## Data Dictionary: 

Column Name | Description
---|---
ID | Unique identifier for the record.
Date | Date when the incident occurred
Primary Type | The primary description of the IUCR code.
Description | The secondary description of the IUCR code, a subcategory of the primary description.
Location Description | Description of the location where the incident occurred.
Arrest | (T/F) Indicates whether an arrest was made. 
Domestic | Indicates whether the incident was domestic-related
Beat | Indicates the beat where the incident occurred. A beat is the smallest police geographic area
District | Indicates the police district where the incident occurred. 
Ward | The ward (City Council district) where the incident occurred
Latitude | The latitude of the location where the incident occurred
Longitude | The longitude of the location where the incident occurred


### Data sourced from: 
* City of Chicago Data Portal - https://data.cityofchicago.org/

# Methods: 
* Prepared data for analysis by combining individual years of crime data into one dataframe.
* Prepared a datetime index in order to perform time series analysis on crime data.
* Answered various reporter questions by creating various visuals to aid in explanations. 
* Created interactive Tableau dashboard presentation with filters to focus on one particular year or one particular district's crime data.

# Results: 

### Total Crime Over Time
![totalCrimeOverTime](https://user-images.githubusercontent.com/112730629/223283878-61b02df5-f5aa-4450-bba3-5d9b5f494e8e.jpeg)

* Crime has decreased significantly from 2001-2023.
* Annual crime numbers have decreased from roughly 500K in 2002 to just over 200K in 2020.


### Crimes by District No.
![crimesByDistrict](https://user-images.githubusercontent.com/112730629/223281787-b05275a2-e4b1-4769-8d48-4064fc41d1d1.jpeg)

* District 8 has the most crime incidents from 2001-2023. 
* District 21 has histrocially had the least crime. 

### Crimes by Month
![crimesByMonth](https://user-images.githubusercontent.com/112730629/223282534-c433e716-c4ad-41fa-997c-bf703679c300.jpeg)
* Peak summer months seem to have the highest frequency of crimes (July, August)
* Peak winter months seem to have the lowest amount of crimes (December, January, February)

### Types of Crime Over Time
![crimeTypesOverTime](https://user-images.githubusercontent.com/112730629/223282038-e1e1efa8-14e1-4901-8521-ba657e8d7f35.jpeg)
* Most types of crime have decreased over the years.
* There are a few outliers (crimes that have increased slightly over time) but the magnitude of their increases has not been very high compared to the amount crimes have decreased over time. 

### Crimes on Holidays
![crimesHolidays](https://user-images.githubusercontent.com/112730629/223283790-0723755b-95ed-4652-9055-0a9deb4cd237.png)
* New Years Day has the highest number of crimes amongst holidays
* July 4th also sees large amounts of crime committed each year


## Tableau Dashboard - Chicago Crime Data
![Screen Shot 2023-02-20 at 2 27 31 PM](https://user-images.githubusercontent.com/112730629/220207557-27fcd4c8-0f9e-422d-b589-cb472633280e.png)


* Link to full Tableau Dashboard: https://public.tableau.com/app/profile/jacob.wang/viz/ProjectDashboard_16764922197350/MainDashboard?publish=yes


# Recommendations to stakeholder: 
* Districts 8, 11, and 25 have above-average crime numbers compared to other districts. 
  * Finding and addressing the root cause of higher crime rates in these areas would lead to better overall public safety. 
* Crime is more frequent during the peak summer months and less frequent during the colder winter months. 
  * Increasing police activity during peak summer months could discourage some potential offenders and may lead to less crime during those months.
* Large numbers of crimes are committed on holidays, especially New Year's Day and July 4th. Increasing police activity during holidays to address the uptick in crime will lead to better overall public safety. 
