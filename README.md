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

#### i. Dashboard
This component provides COVID-19 forecasts with respect to New cases, deaths and tests that would be conducted (based on the new cases). The forecasts are done by analyzing the past county-wise statistical trends. We have made use of time-series model and implemented it using Tensorflow and LSTMs (Long-Short Term Memory). 

These predictions depend on various input factors such as Past New COVID-19 Cases, past deaths due to COVID-19, past tests being conducted, population of the county, Area of the county, and population-density of the county. We have trained the model for 1500 epochs and have achieved an accuracy of ~95%. 

This component has two types of outputs-

a. Next 5-days county-wise forecast charts

<img src="screenshots/dashboard - forecasted statistics.JPG" alt="drawing" width="800" height="400"/>

> https://team6-covid-forecasting.herokuapp.com/

b. Geo-spatial maps of the next 1-day forecast

<img src="screenshots/dashboard - forecasted covid count.JPG" alt="drawing" width="800" height="400"/>

> https://team6-forecast-covid-count.herokuapp.com/

<img src="screenshots/dashboard - forecasted covid death.JPG" alt="drawing" width="800" height="400"/>

> https://team6-forecast-covid-deaths.herokuapp.com/

<img src="screenshots/dashboard - forecasted covid test.JPG" alt="drawing" width="800" height="400"/>

> https://team6-forecast-covid-test.herokuapp.com/


The above outputs are integrated into the app and they can also be accessed using the above mentioned URLs.


#### ii. Realtime Population Density

<img src="screenshots/population density.JPG" alt="drawing" width="800" height="400"/>


#### iii. US State-wise Policy Checker
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

<img src="screenshots/policy checker.JPG" alt="drawing" width="800" height="400"/>


#### iv. COVID-19 Daily News
This section of the app updates daily and displays all the latest news related to COVID-19. The source of the news is Google News. The news are presented in the form of headlines along with the publishing date and the respective source URL for additional information.

<img src="screenshots/covid daily news.JPG" alt="drawing" width="800" height="400"/>

> https://team6-covid-daily-news.herokuapp.com/

#### v. Miscellaneous


## 3. Steps

#### i. Steps to execute the app

1. Fork the project repository by clicking on the 'Fork' button near the top right of the main repository page. This creates a copy of the code under your GitHub user account.

2. Clone your fork of the Product_Team06 repo from your GitHub account to your local disk.
> $ git clone git@github.com:<your GitHub handle>/Product_Team06.git
> $ cd Product_Team06

3. Go to "popul app tempelate/starter-template" directory, run index.html locally. (If in VScode, right click open live server) This will take you to the default home page of the app. (Note: The app is currently designed for low-resolution devices and hence do not open the app in full-screen mode in the browser). 

#### ii. Steps to contribute to the app

1. Add the base repository as a remote:
> $ git remote add upstream https://github.com/peter536/Product_Team06.git

2. Create a feature branch to hold your development changes:
> $ git checkout -b my-feature

Always use a feature branch. It's good practice to never routinely work on the master branch of any repository. 

3. Develop the feature on your feature branch. Add changed files using git add and then git commit files:
> $ git add modified_files
> $ git commit -m "commit message here"

to record your changes locally. After committing, it is a good idea to sync with the base repository in case there have been any changes:
> $ git fetch upstream
> $ git rebase upstream/master

Then push the changes to your GitHub account with:
> $ git push -u origin my-feature

4. Go to the GitHub web page of your fork of the ArviZ repo. Click the 'Pull request' button to send your changes to the project's maintainers for review. This will send an email to the committers.


## 4. Important URLs hosted for the app

#### COVID-19 Indiana County-wise Forecasting (Forecast Graphs)
> https://team6-covid-forecasting.herokuapp.com/

#### Indiana County-wise 1-day COVID Count Forecast (Geomap)
> https://team6-forecast-covid-count.herokuapp.com/

#### Indiana County-wise 1-day COVID Deaths Forecast (Geomap)
> https://team6-forecast-covid-deaths.herokuapp.com/

#### Indiana County-wise 1-day COVID Test Forecast (Geomap)
> https://team6-forecast-covid-test.herokuapp.com/

#### COVID-19 Daily News
> https://team6-covid-daily-news.herokuapp.com/



## 5. Datasets Used & External Source of Information
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


## 6. Meet the Team!
1. Alex Peterson   - https://www.linkedin.com/in/alex-j-peterson/
2. Connor Krehbiel - https://www.linkedin.com/in/connor-krehbiel/
3. Erica Gregg     - https://www.linkedin.com/in/erica-gregg-3a643918a/
4. Moya Zhu		   - https://www.linkedin.com/in/moya-zhu-b93283173/
5. Nicholas Ceglio - https://www.linkedin.com/in/nick-ceglio-116240181
6. Sudip Padhye	   - https://www.linkedin.com/in/sudippadhye/

#### Mentors
1. Libby Ball      - https://www.linkedin.com/in/libby-ball-a5537737/
2. Jeffrey Walters - https://www.linkedin.com/in/jeffrey-walters-60269416/