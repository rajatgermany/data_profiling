# Data Profiling Dashboard
Minimalistic dashboard framework to have a quick look to the structured data

## Sample Dashboard - http://34.65.232.171/

## Features
- Currently dashboard shows three three sections - Missing Values, Categorical Data,  Numerical Data
- Highly adaptable to new data with little to no configuration.

![alt text](./img/demo_2.png)


## Technical Details
- It is built using plotly dash libary along with data manipulation using pandas as numpy
- It is developed in dockerized envoirment and is deployed to google kubernetes cluster.

## How to Use
  - Add the train.csv in the base_data directory 
  - Run dashboard.py
