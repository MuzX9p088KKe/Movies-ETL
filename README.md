# Movies-ETL

## Purpose
This project required a movie database to be put together data from wikipedia, a Kaggle database,and MovieLens ratings data.
In order to keep the database updated on a daily basis an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables was created.
It works by taking in the three files —Wikipedia data, Kaggle metadata, and the MovieLens rating data— and performs the ETL process by adding the data to a PostgreSQL database.


Each user should download the data from the Resources files along with the MovieLens rating data. 
The config.txt file should be changed to config.py and filled with the SQL database password as db_password and the directory of the data files as file_dir.
