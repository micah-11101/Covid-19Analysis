# Covid-19 Analysis
Group Members: 
Viktor, Samantha, Nicholas, Mysee, Micah

# Overview / Research Questions
The COVID-19 pandemic forced the entire world into a new era, for better or worse. In monitoring and managing novel diseases, both the WHO and CDC collected a broad amount of data on a daily basis from 01/11/2020 up until 03/09/2023. We used this data to examine multiple topics, from infection rates between high-population density areas and low-density areas. In addition to that we looked at analyzing the effects of the virus on education attainment.

## Research Questions and Motivations
The members in our group were each individually interested and – of course, impacted by the pandemic, and were interested in investigating potential relationships between COVID-19 and our topics.

1. How did COVID infections impact areas of higher population density than areas of lower population density?

2. How did our tourism economy perform prior to and during Covid?

3. How did COVID affect education?

# Data Exploration and Clean-Up Process
The data we downloaded from John’s Hopkins’ GitHub repository was in .csv format, meaning that it was readily available to be uploaded into our Jupyter Notebook. The data was cleaned and standardized, making sure we have uniform column headings. We ran tests to check and ensure we had all and only the unique languages in our dataset. 

# Data Analysis Process
To do the analysis, we ran a few different tests and presentations on the data:

We compared tourist revenue to new covid cases by line plotting them on separate axises and comparing them overtime.

The COVID-19 infection data was pulled from the John Hopkins GitHub repository. It was cleaned and then extracted into new data frames for Minnesota and the United States. Bar charts were used to visualize the total COVID-19 infections for Minnesota (by county) and the United States (by state). Line graphs were used to visualize the top five counties in Minnesota with the highest COVID-19 infections from February 2020 to February 2023 and the top five states with the highest COVID-19 infections from February 2020 to February 2023.

Found the percentages of people with different education levels. Then merged the data and then made a stacked bar graph for MN counties. 
Next, made a CSV file for the education levels from the Census Bureau and compared them over time to see what changed from 2016-2022. Then with the same data got the percentages from the population and compared them with bar graphs. 
Finally, with the Census Bureau, for different education levels of people aged 18-24 in the years 2019 and 2022. Then used that data to make a line graph and three different bar graphs. 

# Hypothesis Testing
We tested multiple different hypothesis:

GeoPolygon Plot
We created a plot that displays the change in reported cases that is run on a per 100k population basis to give a better understanding of the change over time. 


# Conclusion


We can conclude that government policies impacted tourism revenue more than covid infections did based on the fact that there is not a significant negative correlation between the two.

Minnesota’s highest total COVID-19 infections were Hennepin county, Ramsey county, Anoka county, Dakota county, and Washington county. These counties are also a part of Minnesota’s Twin Cities metropolitan area where it is highly dense with residential and commercial zones. The other counties of Minnesota were also infected with COVID-19 but their total infections were not as high in count.
The United States’ total COVID-19 infections were California, Texas, Florida, New York, and Illinois. These states are states with high traffic of tourism and large metropolitan cities. The other states and provinces were also infected with COVID-19 but their total infections were not as high in count.

Education was not negatively affected by Covid, it seemed to be beneficial in most states. 


# Citations
https://medium.com/@alex_44314/use-python-geopandas-to-make-a-us-map-with-alaska-and-hawaii-39a9f5c222c6
> Used this to create the visualization of the map
https://hdpulse.nimhd.nih.gov,   http://hdpulse.nimhd.nih.gov/data/dictionary.php#education,   https://data.census.gov/table?q=state+population+by+education
> Made csv files with these
