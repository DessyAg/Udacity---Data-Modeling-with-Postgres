## DATA MODELING with PostgreSQL

#### Introduction

    A startup called Sparkify needs to analyze the information they've been collecting on songs and user activity on their new music streaming app. 

    It is my job to create the database schema and ETL pipeline for this analysis.
    
#### Project Description
   
    In for this project, I will do some steps:
    1. I use Postgres as the database and Python for the ETL pipeline.
    2. On the other hand, I will define fact and dimension tables for the star schema for  specific analysis focus
    
     This is Schema for Song Play Analysis
     
     Fact table :
     songplays => songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent
        
     Dimension Tables :
     users     => user_id, first_name, last_name, gender, level
     songs     => song_id, title, artist_id, year, duration
     artists   => artist_id, name, location, latitude, longitude
     time      => start_time, hour, day, week, month, year, weekday


#### Project Goal

    1. Review and Analyze Datasets
    2. Setup Database in python
    3. Setup ETL to the Postgres table
    4. Doing Analytics Queries

     
#### Project Steps
       
     1. Write CREATE statements and DROP(each table if it exists) in SQL_queries.py in python.
     2. Run create_tables.py to create database and tables in python.
     3. In Jupyter Notebook (ETL.ipynb) develop ETL processes for each table (Load from a file song_data and log_data into Jupyter Notebook).
     4. Run test.ipynb (Jupyter Notebook) to confirm your records were successfully inserted into each table.   

    
    

