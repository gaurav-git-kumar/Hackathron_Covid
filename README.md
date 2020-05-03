# Hackathron_Covid

This ML model is made to visualise the covid 19 and its impact on india and the world
This model also predicts The increase in Covid cases and deaceased patients using Polynomial Regression

The prerequisite for This notebook is-
folium ,cufflinks,seaborn,pandas , numpy , matplotlib

This model gets latest updated data from following sorces
Data Sorces are -
1. https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv
2. 'https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv'
3.ind_comp = pd.read_csv('../input/covid19-corona-virus-india-dataset/complete.csv')
4.ind_patient = pd.read_csv('../input/covid19-corona-virus-india-dataset/patients_data.csv')

Many types of graphs has been plotted this can be seen by clicking on external view with nbviewer in github

The graphs help in understanding the trend of increase in Covid 19 cases
Feature engineering has been done for graphs involving Time Series and Mortality rate graphs

A corrilation matrix has been made which shows strong corrilation of Deaths with Total number of Confirmed cases and Mortality rate etc. which is as expected.

Daily increase in Covid cases in India is plotted using Seaborn and cufflinks
