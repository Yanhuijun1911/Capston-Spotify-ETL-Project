# Capston-Spotify-ETL-Project

This is the capston project completed at the end of the training of data engineering at Digital Futures.

The aim of the project is to present the ETL (extracting, transforming, loading) process of data from Spotify my playlist, preparing for the data for further analysis.


## Data Extracting

The Spotify API was applied to extract the data of a playlist named [my playlist] from my personal account. 

<img width="1051" alt="Screen Shot 2023-01-13 at 12 04 38 pm" src="https://user-images.githubusercontent.com/97167097/212316420-49359c04-1743-4484-90f6-ffa34c433149.png">

The tracks, their features of the tracks, and the artists of the tracks of [my playlist] were extracted as well as the artists of top tracks.


## Data Transforming

Data cleaning and transforming were conducted arfter extracting the data.

Designed a schema to structure the original dataset and created a new structure of the data.

<img width="683" alt="Screen Shot 2023-01-13 at 12 07 34 pm" src="https://user-images.githubusercontent.com/97167097/212316957-8649ed07-086e-4654-b912-4f8f3b8abbc0.png">

<img width="722" alt="Screen Shot 2023-01-13 at 12 07 42 pm" src="https://user-images.githubusercontent.com/97167097/212316996-3cfb1596-b8ca-4efd-9760-51cda0adbafd.png">


## Data Loading

Loaded the data to the database using SQL.
