# Public Shootings and Taxi: Risk Analysis & Minimization
> by Shromann Majumder
---
This Project aims to **Explore**, **Analyse** and **Model** *Public Shootings Risk NYC Cars Face*, as well as propose a solution to *minimize* this risk. 

## Important Note
If you're running for the first time, please run `Exploratory Analysis.ipynb`'s first code cell to download the data.

## Dependencies
- Language: Python 3.8.3
- Packages / Libraries: pandas, pyspark, sklearn, scipy, folium, geopandas, math, plotly, matplotlib, os, urllib, zipfile. 

## Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page (April - June 2019): Taxi Pick Up/Drop Off Time and Locations 
- Taxi Zone: https://s3.amazonaws.com/nyc-tlc/misc/taxi\_zones.zip: Taxi Pick Up/Drop Off Geometerical Shapes for Geospatial Analysis
- NYPD Shootings: https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8: NYPD Shootings Time and Location

## Directory
- `raw_data`: ALl Datasets used are stored here
- `plots`: All plots are saved here
- `Exploratory Analysis.ipynb`: Notebook where we conduct Exploratory Analysis
- `Risk Analysis & Modelling.ipynb`: Notebook where we Analyse and Model Risk of Taxi, as well as propose a solution.
