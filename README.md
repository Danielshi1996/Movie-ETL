# Movie-ETL

## Overview

The purpose of this project is to practice the process of data ETL using python, pandas, re, and sqlalchemy modules, as well as PosgreSQL database. Data sources includes Kaggle movie data, Kaggle movie rating data, and JSON format movie data from wikipedia, which has been included in the resources folder.

## Result

Each of the ipynb file contains data cleaning process of the data mentioned in the file name.

### ETL_function_test.ipynb

This file contains the process of data extraction. The wiki movie raw data has been inclueded as csv file in the resources folder as well as Kaggle movie data. The Kaggle rating data was not included due to file size being too large. Running this code will display raw data dataframes.

### ETL_clean_wiki_movie.ipynb

The code contains the process of cleaning the wiki movie data, including removing unnecessary columns and parsing inconsistent data. Running this code will display cleaned dataframes.

### ETL_clean_kaggle_data.ipynb

The code contains the process of cleaning Kaggle movie data and Kaggle ratings data, as well as merging with the wiki_movie_df from previous code. Running this code will display cleaned dataframes.

### ETL_create_database.ipynb

This code will load cleaned movie dataframe and the raw Kaggle rating data in to PosgreSQL database.
