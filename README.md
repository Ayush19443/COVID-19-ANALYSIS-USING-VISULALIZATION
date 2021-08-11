# COVID-19-ANALYSIS-USING-VISULALIZATION
INTRODUCTION
Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus.
Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment.  Older people, and those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory disease, and cancer are more likely to develop serious illness.
The best way to prevent and slow down transmission is to be well informed about the COVID-19 virus, the disease it causes and how it spreads. Protect yourself and others from infection by washing your hands or using an alcohol based rub frequently and not touching your face. 
The COVID-19 virus spreads primarily through droplets of saliva or discharge from the nose when an infected person coughs or sneezes.
Amid a barrage of information on Covid-19, processing the relevant material can be challenging. While some have completely disconnected themselves from the news cycle, others are regularly tracking their news feed to better understand how to combat Covid-19.
 Data Visualization have allowed us to understand and absorb information in a quick and accurate manner.
 
MOTIVATION AND METHODOLOGY FOLLOWED
As cases of Covid-19 proliferate across the globe, so has data associated with it. This data includes the confirmed cases, death and recovery rates.
This data needs to be efficiently conveyed to people, since in the event of a pandemic like this, intuition cannot substitute for facts to understand how the spread is advancing.
When dealing with quantitative data that is so large, data visualization helps people to feel like they can understand the world around them.
This motivated me to do this project.
TOOLS/LANGUAGE USED
Python
Numpy
Pandas
Matplotlib
IBM Cloud
OVERVIEW
The project starts by importing the necessary libraries/packages which have been used throughout the project.
Next, we imported our dataset which is a csv file. This csv file is updated daily therefore, we always get the current fresh data.
The URL for the dataset is: https://raw.githubusercontent.com/datasets/covid-19/master/data/countries-aggregated.csv
Our dataset contains 58828 rows and 5 columns.
Our data frame has the following columns:
Date🡪 entries starting from January 22.
Country🡪 name of countries; 191 distinct countries.
Confirmed🡪 total number of confirmed cases.
Recovered🡪 total number of recovered cases.
Deaths🡪 total number of deaths.
We plot the pie chart of the world showing the total percentage of Confirmed, Recovered, and Death cases.
