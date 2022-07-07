# Predicting Flight Delays


There are 7 Jupyter Notebooks for this project, they should be read in this order:
* Cleaning_and_Preprocessing_2020_Data
* Cleaning_and_Preprocessing_2021_Data
* Exploratory_Data_Analysis
* Balancing_Target_Classes
* Logistic_Regression
* Decision_Tree
* XGBoost

Flight data were downloaded from the [The Bureau of Transportation Statistics](https://transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGJ&QO_fu146_anzr=b0-gvzr). This data consists of USA domestic flight data for 2020 and 2021.

I have chosen to focus on Hartsfield-Jackson Atlanta International Airport only as it is the most popular origin airport in this data set (and the 2021 data set as well).

In addition, I have added weather data for Hartsfield-Jackson Atlanta International Airport downloaded from [NOAA](https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00013874/detail), and estimated state populations from [The United States Census Bureau](https://www.census.gov/data/datasets/time-series/demo/popest/2020s-state-total.html#par_textimage_1873399417). 

