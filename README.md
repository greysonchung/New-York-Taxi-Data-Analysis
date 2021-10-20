# MAST30034 Project 1
- Student Name: Haonan Zhong
- Student ID: 867492
- Due Date: Monday 16th of August 11:59:00 am (AEST).
- Report Link: https://www.overleaf.com/read/zfqfjgfrxdnh


 # Dependencies
 - Language: Python 3.8.8
 - Python Packages / Libraries: pandas, geopandas, numpy, matplotlib, seaborn, scipy, sklearn, statsmodels, contextily

 # Datasets
 - NYC TLC (Jan, Feb, Jul, Aug of 2018): https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
 - NYC Taxi Zone Shapefile: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
 - NYC Central Park Weather Record (2018): https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00094728/detail
 - To download NYC TLC datasets please locate `download.ipynb` included in `code`, Taxi Zone Shapefile and weather dataset has been included in `raw_data`.

 # Directory
 - `raw_data`: Contains all the raw data files. Added to `.gitignore`
 - `preprocessed_data`: Contains all the preprocessed data files. Added to `.gitignore`
 - `plots`: Contains all visualisation plot for the project.
 - `deprecated`: Contains all the old code that I don't use anymore.
 - `code`: Contains notebooks for Preprocessing, Visualisation, and Modelling.
    - `download.ipynb` for "Downloading" trip record datasets.
    - `preprocessing.ipynb` for "Preprocessing" and "Exploratory Data Analysis".
    - `visualisation.ipynb` for "Analysis and Visualisation".
    - `modelling.ipynb` for "Statistical Modelling".
 - To reproduce the results, simply download all the dataset and run each notebook.