# Rat Population Data Analysis - New York City

<hr>

## Descriptions of Datasets

### Rat dataset

https://data.cityofnewyork.us/Social-Services/Rat-Sightings/3q43-55fe

Our analysis primarily revolves around this dataset, with several supplementary datasets appended to this one for further in-depth analysis. This dataset contains 208,000 different rat sightings in the City of New York between 2010 to the present day, reported by citizens to the City of New York and accessed from NYC Open Data. 38 different variables are recorded for each sighting; notably, geographic data such as latitude, longitude, and borough data, and the date of opening and closing of the complaint. 

### Supplementary Datasets

We join various auxiliary datasets (described below) to our rat sightings dataset in order to better examine how rat sightings correlate to other demographic and geographic factors.

#### Subway Dataset

https://data.cityofnewyork.us/Transportation/Subway-Entrances/drex-xx56

This dataset, also sourced from NYC Open Data, contains the names, line numbers, and geographic coordinates of 1928 subways in New York City to date.

#### Tax Return Dataset

https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-zip-code-data-soi

This is an 2019 IRS-sourced dataset which contains tax return information for each of the 178 zip codes in NYC; namely, the number of returns and total amounts requested by eligible citizens of each of the zip codes for their individual tax returns.

#### Restaurant Inspection Dataset

https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j

This is an NYC Open Data dataset, most recently updated on December 10, 2022, containing 231,000 data, each corresponding to a health violation citation given to a restaurant in NYC by the City of New York's Health Department. We are given 27 different variables that most importantly provide the location and zip code of each restaurant which was issued a citation.

<hr>

## Research Questions

Going into this project, our group had several questions we wanted to answer regarding the distribution of rats in the city. Namely:

* How do rat sightings differ geographically and by borough?
* How has the number of rats reported changed over time?
* How does well do wealth and geographic data combined correlate with rat sightings?
* How do rat sightings correlate with candidate features such as subways and restaurants?


In all, we hope to make underlying observations that extend beyond the mere topic of rats, using rat sightings as a proxy for deeper conclusions about socioeconomic and geographic patterns in the City of New York.

