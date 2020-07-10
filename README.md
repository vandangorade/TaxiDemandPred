# TaxiDemandPred
 predict the Demand of Yellow Taxi in New York City at given location and at a given time interval.

![alt text](https://i.imgur.com/GNbWoOk.jpg)

## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [License](#license)
* [Acknowledgements](#acknowledgements)


<!-- ABOUT THE PROJECT -->
## About The Project

### Problem Statement

For any given Location in New york city predict the number of pickups at that location

## Approach

 Convert the given time series data into 10 minute interval bins.
 
 Break the region of new york city into some clusters say k.
 
 Group the time series data for each cluster.
 
 Apply any feature engineering techniques to generate some more time series features.
 
 Perform Train-Test Split.
 
 Train Models.
 
 Evaluate and Display MAPE in Tabular Format for all the models built.

### Built With
```sh
 python
 sklearn
 Dask
 matplotlib
 seaborn
 folium
```
<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Data Source: https://www.nycyellowcabtaxi.com/
