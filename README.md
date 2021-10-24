# Movies-ETL
This project conducts a thorough ETL on data, cleaning it in Python and loading it into a SQL database. 

## Purpose
* The purpose of this project was to analyze movie data from Wikipedia and Kaggle and combine them based on imdb ID. This was done with Python, several large data files were imported, in multiple formats (JSON and CSV) and the data was cleaned within a function. The analysis included using the following libraries: json, pandas, numpy, sqlalchemy, and time. The function cleaned the data uploaded the completed file as a SQL library. 

## Results
* The original data file of wiki movies include 7311 rows and 193 columns. This data was cleaned to only include movies (the item of interest in this analysis) as well as transform multiple other columns into usable and uniform data sources. The result was 6052 rows and 21 columns. Kaggle data was also cleaned and joined to wiki data. The Kaggle data was redundant in some situations and also contained less errors, so it filled in null values and replaced some columns of the wiki data. 
   
* Finally the ratings data was also joined, based on imdb id. The final data is clean and usable.  As an extra value add, a brief print statement was added to the upload of the ratings data to show which chunk of data was currently uploading and the time it took to upload such a large file. 
* The attached results show the movies data row count and ratings row count after they were uploaded to the SQL data base. ![Movies Query](https://github.com/Mary-Wood/Movies-ETL/blob/main/Resources/movies_query.png), ![Ratings Query](https://github.com/Mary-Wood/Movies-ETL/blob/main/Resources/ratings_query.png)

