## Project Description:

This Python script is designed to collect information about the top 50 movies from a specific webpage using web scraping techniques. The gathered data includes essential details such as movie titles, release years, and average rankings. While these details are stored in a CSV file, they are also saved into a SQLite database named Movies.db, creating a table named "Top_50."

## Technologies Used:

Python
Beautiful Soup (for web scraping)
SQLite (for database operations)

Utilizing Beautiful Soup library for web scraping, this project extracts data from the specified website and saves the acquired information into both a CSV file and an SQLite database. This setup enables similar entities to analyze and utilize the data as needed.


## Collecting Data of Top 50 Films Using Web Scraping

This Python script is designed to retrieve information about the top 50 films from a web source on behalf of a Multiplex management organization. The data is extracted from (https://web.archive.org/web/20230902185655/https://en.everybodywiki.com/100_Most_Highly-Ranked_Films).

## Data Extracted:

Average Ranking
Film Title
Release Year
CSV File: top_50_films.csv

The relevant information has been exported to a CSV file.
Database: Movies.db (Table Name: Top_50)

The same dataset has been stored in the Movies.db database under the table name Top_50.
