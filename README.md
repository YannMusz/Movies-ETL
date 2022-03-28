# Movies-ETL


## Purpose
The projects purpose was to extract data from the Kaggle meta data, and making it into a useable data set. Once the data was transformed , the DataFrames were loaded into PostgresSQL.  

1. Create an ETL from the raw data provided to a SQL database.
2. Transform the data provided using Pandas
3. Load data with PostgreSQL and verify in PgAdmin.


## Extracting
Wikipedia Movies JSON file
![Pic 1](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d1_1wiki_movies.PNG)

The Kaggle Movie Metadata, 24 columns
![Pic 2](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d1_2kaggle_metadata.PNG)

The Kaggle Ratings data, 2602489 rows by 4 columns

![Pic 3](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d1_3ratings.PNG)

## Transforming 
### Wikipedia Data
Wikipedia Movies transformed, 22 columns
![Pic 4](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d2_1wiki_movies.PNG)

Wikipedia Movies, making the column names more succinct and uniform, 7033 rows of data.
![Pic 5](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d2_2wiki_movie_counts.PNG)

### Kaggle Data
Wikipedia Movies merged with Kaggle Movies data, all column names and row counts, 6052 rows.
![Pic 8](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d3_6movies.PNG)

Merged Movies with Kaggle ratings, all of the column names and row count.

![Pic 9](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d3_5movies_ratings.PNG)

## Loading
### Creating the Movie Database
Sending the data to PostgresSQL
![Pic 10](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/d4_final_send.PNG)

### Verifying the data with the use of PgAdmin
Movies Query

![Pic 11](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/movies_query.PNG)

Ratings Query

![Pic 12](https://github.com/YannMusz/Movies-ETL/blob/main/Resources/ratings_query.PNG)

## Summary

 JSON file and two Kaggle data sets were extracted for the project and then joined together.  
