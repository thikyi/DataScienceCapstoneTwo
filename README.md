# Los Angeles County Crime Rate Predication

## Context
Los Angeles has a crime rate of 2,759 per 100,000 people, which is higher than the national average of 2,580 per
100,000 people.I developed a machine learning model that integrates demographics, and
historical crime reports to predict the likelihood of specific crimes occurring in specific
areas within Los Angeles.By providing a data-driven crime prediction model , policy makers and
certain communities can be empowered to implement targeted security measures and
make informed decisions.

## Project Approch

### Data Acquisition
The necessary data was accquired from the provided sources:
- Crime data from 2012 to the present will provide historical crime reports.Crime
Datasource includes Date Rptd,DATE OCC,TIME OCC,AREA,AREA NAME,Rpt Dist
No,Part 1-2,Crm Cd,Crm Cd Desc,Mocodes,Vict Age,Vict Sex,Vict Descent,Premis
Cd,Premis Desc,Weapon Used Cd,Weapon Desc,Status,Status DescLOCATION,Cross
Street,LAT,and LON).
### Solution Overview

1. Data Waggling: Cleaning and integrating demographics, and historical crime
reports, Crime Location,General Crime type,Occurred date will be used as
primary data. And, matching crime location with current location to find out the
where is the most common place that current businesses are operating.
2. Exploratory Data Analysis: Statistically exploring the dataset to understand its
characteristics, patterns, and potential issues, and creating relevant features that
capture the characteristics of crime areas.
3. Preprocessing & Training: Building a machine learning model (e.g., a predictive
classifier or regressor) that utilizes historical crime data and area features to
predict future crime rates.
4. Modeling: Assessing the model's performance using appropriate metrics such as
MAE,MSE and RMSE.

### Files


