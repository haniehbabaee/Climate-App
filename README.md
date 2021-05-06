# Climate-App
It analyzes the weather data for Hawaii collected at various weather stations to predict typical weather during the trip. This is done in the Jupyter notebook, while a Flask app is also created that allows data calls from a SQLite database using SQLAlchemy and Flask.

![surfs-up](https://user-images.githubusercontent.com/70447525/117233367-fb038400-adf0-11eb-8527-f7812879871e.png)

## Precipitation Analysis
Design query to retrieve the last 12 months of precipitation data.

Plot query results using pandas.

<img width="468" alt="precipitation" src="https://user-images.githubusercontent.com/70447525/117234035-3ce0fa00-adf2-11eb-8f37-ac254aeaabd2.png">

## Station Analysis
Design a query to calculate the total number of stations.

Design a query to find the most active stations.

Design a query to retrieve the last 12 months of temperature observation data (TOBS).

<img width="478" alt="station-histogram" src="https://user-images.githubusercontent.com/70447525/117234158-70238900-adf2-11eb-8913-48c5a24c8f19.png">

## Climate App

Create a Flask API based on the queries that developed with two Routes.

