# COVID Detection (Team 06)
This project repository is the part of Techpoint's S.O.S. challenge - 2020. It consists of "COVID DETECTION" activites and developing an app which serves as a one-stop & quick-access solution for a layman covering majority of the COVID-19 related contents, without searching on Google.

## 1. Introduction
In this project, we (Team-06) have implemented various measures and details related to the novel coronavirus COVID-19. For this, we have analyzed the past data, displayed the present scenario and forecasted future trends. 

Below are the main components of our app-

i.   Dashboard

ii.  Realtime Population Density

iii. US State-wise Policy Checker

iv. COVID-19 Daily News

v.  Miscellaneous (Nearest COVID Testing center, COVID symptoms, Developer's bio, Bug reporting)


## 2. Components

### i. Dashboard
This component provides COVID-19 forecasts with respect to New cases, deaths and tests that would be conducted (based on the new cases). The forecasts are done by analyzing the past county-wise statistical trends. We have made use of time-series model and implemented it using Tensorflow and LSTMs (Long-Short Term Memory). 

These predictions depend on various input factors such as Past New COVID-19 Cases, past deaths due to COVID-19, past tests being conducted, population of the county, Area of the county, and population-density of the county. We have trained the model for 1500 epochs and have achieved an accuracy of ~95%. 

This component has two types of outputs-

a. Next 5-days county-wise forecast charts

[https://team6-covid-forecasting.herokuapp.com/]

b. Geo-spatial maps of the next 1-day forecast

[https://team6-forecast-covid-count.herokuapp.com/]

[https://team6-forecast-covid-deaths.herokuapp.com/]

[https://team6-forecast-covid-test.herokuapp.com/]


The above outputs are integrated into the app and they can also be accessed using the above mentioned URLs.


### ii. Realtime Population Density


### iii. US State-wise Policy Checker
This component of our app provides realtime COVID-19 US statewise policies pertaining to various aspects:

a. Bar Closures

b. Emergency Declaration

c. Face Covering Requirement

d. Large Gatherings Ban

e. Mandatory Quarantine for Travelers

f. Non-Essential Business Closures

g. Primary Election Postponement

h. Restaurant Limits

i. School Closures

j. Status of Reopening

k. Stay at Home Order

These policies are represented in the geomap with different color schemes for different policies.

[https://team-6-policy-map.herokuapp.com/]

### iv. COVID-19 Daily News
This section of the app updates daily and displays all the latest news related to COVID-19. The source of the news is Google News. The news are presented in the form of headlines along with the publishing date and the respective source URL for additional information.

[https://team6-covid-daily-news.herokuapp.com/]

### v. Miscellaneous




## 3. Important URLs hosted for the app

### COVID-19 Indiana County-wise Forecasting (Forecast Graphs)
> https://team6-covid-forecasting.herokuapp.com/

### Indiana County-wise 1-day COVID Count Forecast (Geomap)
> https://team6-forecast-covid-count.herokuapp.com/

### Indiana County-wise 1-day COVID Deaths Forecast (Geomap)
> https://team6-forecast-covid-deaths.herokuapp.com/

### Indiana County-wise 1-day COVID Test Forecast (Geomap)
> https://team6-forecast-covid-test.herokuapp.com/

### Policy Map
> https://team-6-policy-map.herokuapp.com/

### COVID-19 Daily News
> https://team6-covid-daily-news.herokuapp.com/



## 4. Datasets Used & External Source of Information
a] Indiana County-wise COVID Cases, Deaths, Tests
> https://hub.mph.in.gov/dataset/bd08cdd3-9ab1-4d70-b933-41f9ef7b809d/resource/afaa225d-ac4e-4e80-9190-f6800c366b58/download/covid_report_county_date.xlsx?raw=true

b] Indiana County-wise Population and Area
> https://en.wikipedia.org/wiki/List_of_counties_in_Indiana

c] Indiana County FIPS code
> https://en.wikipedia.org/wiki/List_of_counties_in_Indiana

d] COVID-19 Symptoms & Precautions
> https://www.cdc.gov/

e] Nearest COVID-19 testing center
> https://www.anthem.com/microsites/covid19-assessment/covid-finder.html




## 5. Meet the Developers!
(profile picture of the team)