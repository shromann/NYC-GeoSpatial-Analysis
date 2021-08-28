# Public Shootings and Taxi: Risk Analysis & Optimization
> by Shromann Majumder


## Dependencies
- Language: Python 3.8.3
- Packages / Libraries: pandas, pyspark, sklearn, scipy, folium, geopandas, math, plotly, matplotlib, seaborn, os, urllib, zipfile, shutil

## Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page (April - June 2019)
- Taxi Zone: https://s3.amazonaws.com/nyc-tlc/misc/taxi\_zones.zip
- NYPD Shootings: https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8


## Directory
- `raw_data`: Contains all the raw data files. You may add this folder to `.gitignore` if your files are too large, but you **must** provide code to automatically download or links so that we may manually download them. 
- `preprocessed_data`: Contains all the preprocessed data files. You may add this folder to `.gitignore` if your files are too large, but your script should automaticaally generate files here given the correct dataset in `raw_data`.
- `plots`: Output and save all your figures here.
- `code`: Keep all notebooks and scripts in this folder. Ensure that you have notebooks for each _stage_ of code. Here's an example:
    - Notebook 1 for All basic plots and experimentation
    - Notebook 2 for All complex plots
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. This is useful in case you ever need to come back to an older iteration of code or to express your other approaches to the problem.



