# Movies-ETL

## Overview & Purpose
We have created this script to facilitate the creation of an automated pipeline that takes in new data, performs the appropiate transforations, and loads the data into existing tables.

In this script we have created one function that takes in three files (*Wikipedia data, Kaggle ,metadata, and MovieLens rating)*, performs the ETL process, and adds the data to a PostgreSQL database. 

The script has been devided into four technical analysis deliverables: 

- ETL_function_test.ipynb- *ETL Function to Read Three Data Files.
- ETL_clean_wiki_movies.ipynb- *Extract and Transform the Wikipedia Data.
- ETL_clean_kaggle_data.ipynb- *Extract and Transform the Kaggle data.
- ETL_create_database.ipynb- *Create the Movie Database.
