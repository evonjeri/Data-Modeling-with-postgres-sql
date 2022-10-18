# Project: Data Modelling with Postgres
### Introduction
> A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. 
> The purpose is to create a Postgres database with table designed to optimize queries on song play analysis. In this project, data modeling with Postgres and building ETL pipeline using python skills is required. To complete, there is need to define fact and dimension tables for Star schema and write ETL pipeline that transfers data from files in two local directories into these tables in progress using python and SQL.

### Dataset 
> This project has two datasets; song_data and log_data. The song_data is a subset of real data from Million Song dataset and each file is in JSON format and contains metadata about song and artist of the song. 
The log_data consists of log files in JSON format generated an event simulator. These simulates activity logs from music streaming app based on specified configurations.

### Run the Python scripts
Open terminal 
Run python create_tables.py 
Same to all the other file.

### Database Schema design and ETL pipeline
>Created a star schema with a fact table (songplays) and 4 dimension tables (songs, artists, time and users).

>Used etl.ipynb notebook to develop ETL process for each table then completed the etl.py and processed the dataset. Afterwards ran test.ipynb to confirm records were successfully inserted into each table.
### Descriptions of files 
> - Create_tables.py – A python script that drops and creates the tables. You run this file to reset your table before each time you run any ETL script.
> - Sql_queries.py – Python script containing all the sql queries in this project.
> - Etl.ipynb – a Jupyter notebook that reads and processes a single file from the song_data and the log_data and loads the data into the tables. This notebook contains detailed instructions of the ETL process.
> - Etl.py – this python file reads and processes file from song_data and log_data and load them into the tables.
> - Test.ipynb – this notebook is used to confirm that records were successfully inserted into each tables.



