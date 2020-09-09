
# Movies-ETL

## Overview of Project
The goal of this assignment is extract movie data and ratings from various sources, clean and organize the data, and load it into an SQL database.

### Results of Employee Retirement Analysis
Below we can see the final counts of the movies and ratings in our database:

Movies Query       |  Ratings Query
:-------------------------:|:-------------------------:
![movie_query](https://raw.githubusercontent.com/si1ver1/Movies-ETL/master/Resources/movies_query.png) | ![ratings_query](https://raw.githubusercontent.com/si1ver1/Movies-ETL/master/Resources/ratings_query.png)

### Summary
The final project is setup to be able to run automatically through a couple functions to read the data, clean it, and copy it to our database using replace. Our two tables movies and ratings are tied together through the movieId.