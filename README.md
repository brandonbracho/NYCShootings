# NYCShootings
For a dynamic view of this Jupyter Notebok please visit: http://nbviewer.org/github/brandonbracho/NYCShootings/blob/main/ShootingsNYC%281%29.ipynb
## Introduction 
This project is part EDA (Exploratory Data Analysis) and part predcitive modeling using the Historic Shooting Incidents and Year to Date Shooting Incidents dataset from NYC's Open Data site. Inspiration for this project ensued in light of the media frenzy that is surrounding the rise of gun violence in New York City. Do the numbers match the hype? Questions that are addressed within the project include:
- What are the overall trends in shootings, along with yearly, monthly and hours trends.
- What factors play a role in the sheer number of daily shootings and could these factors help a preditive model perform better?
- Where do most shootings in NYC occur?
- What are trends seen in the demographics of perpetrators of shootings along with the victims?
- How many total shootings might NYC see in the year of 2021?
# Packages and Resources Used
- **Python Version:** 3.7
- **Packages/Modules:** pandas, numpy, sklearn, folium, datetime, matplotlib, seaborn
- **Data Sources:** https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8 (Historic Shootings), https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Year-To-Date-/5ucz-vwe8 (YTD Shootings), https://www.wunderground.com/ (Historical Weather Data)
- **Papers Cited:** Reeping, Paul M, and David Hemenway. “The association between weather and the number of daily shootings in Chicago (2012-2016).” Injury epidemiology vol. 7,1 31. 22 Jun. 2020, doi:10.1186/s40621-020-00260-3 https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7310019/
# Relevant Findings
## Overview of Dataset
![Image](/images/dataset.png)
[^1]
![Image](/images/dataset%20type.png) 
[^2]
![Image](/images/dataset%20shape.png)
[^3]
![Image](/images/missing%20data.png)
[^4]

[^1]: First five rows of data are being printed. 
[^2]: The dataset type is being shown here along with the count of non-null values. The dataset is composed of mixed types with the majority being strings. 
[^3]: The dataset is composed of 24470 rows and 18 columns. 
[^4]: The dataset is contains very little missing data overall, with every column having under 1% of data being composed of missing values. 

## Time Series Aggregations of Shootings 
![Image](dayswoshootings.png)
[^5]
![Image](/images/dataset%20boxplot.png)
[^6]
![Image](/images/dataset%20kde.png)
[^7]
![Image](/images/feature%20creation.png)
[^8]
![Image](/images/shootingsbydayofweek.png)
[^9]
![Image](/images/shootingsbyhour.png)
[^10]
![Image](/images/shootingsbyyear.png)
[^11]
![Image](/images/shootingsbymonth.png)
[^12]

[^5]: There were a total of 432 days without shootings in NYC between the years of 2006 - 2021.
[^6]: Boxplot of distribution of number of shootings per day. 
[^7]: KDE distribution plot of shootings per day.
[^8]: Creation of time-dependent features, such as Year, Hour, and Month. 
[^9]: Total shootings aggregated by day of week. 
[^10]: Total shootings aggregated by hour.
[^11]: Total shootings aggreagted by year.
[^12]: Total shootings aggregated by month. 















