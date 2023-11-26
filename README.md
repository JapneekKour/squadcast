Data Analysis and Manipulation

1. Data Import:
Setting up a PostgreSQL Database on Render:
Created Tables and Import CSV Data using psql
You would create two tables, one for movies and one for ratings.


2. Insights and Analysis:
Used pycharm to perform Insights and Analysis

ABOUT THE CODE 
Connection and Cursor Setup:
The code established a connection to the PostgreSQL database using the provided external URL and creates a cursor object for executing SQL queries.

Various SQL queries are executed to retrieve information about the top 5 movies based on duration, year, average rating, and the number of ratings given. The results are printed.
Unique Raters Count Query and Print:

A query is executed to count the number of unique rater IDs in the ratings table, and the result is printed.
Top 5 Rater IDs Queries and Prints:

Queries are executed to find the top 5 rater IDs based on the most movies rated and the highest average rating given. The results are printed.
Additional Queries and Prints:

Additional queries and prints are performed for finding the favorite movie genre of a specific rater, the highest average rating for a movie genre by a specific rater, the year with the second-highest number of action movies, and the count of movies with high ratings.

Exception Handling and Connection Cleanup:

Exception handling is implemented to catch any operational errors that may occur during database operations. Finally, the cursor and connection are closed.
This code essentially retrieves and prints various insights and analyses from the PostgreSQL database on Render, based on the specified queries.












































