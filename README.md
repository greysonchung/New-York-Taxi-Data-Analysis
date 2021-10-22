 # Exporatory Analysis of New York City Taxi
 * <img src="https://iconape.com/wp-content/files/ik/11613/png/medium.png" width="15" height="15"/><a href="https://medium.com/@haonanzhong/new-york-city-taxi-data-analysis-286e08b174a1"> Medium Story</a>

`Note: This is just the copy of the original project repository, the original project repository is kept private and is available upon request.`

 ## Dependencies
 - Language: Python 3.8.8
 - Python Packages / Libraries: pandas, geopandas, numpy, matplotlib, seaborn, scipy, sklearn, statsmodels, contextily

 ## Datasets
 - [NYC TLC Dataset (Jan, Feb, Jul, Aug of 2018)](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
 - [NYC Taxi Zone Shapefile](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
 - [NYC Central Park Weather Record (2018)](https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00094728/detail)
 - To download NYC TLC datasets please locate `download.ipynb` included in `code`, Taxi Zone Shapefile and weather dataset has been included in `raw_data`.

 ## Directory
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
