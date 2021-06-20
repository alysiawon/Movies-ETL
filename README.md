# Movies-ETL

## Overview of Project

The purpose of this project is to assist the Amazing Prime to develop an algorithm to determine which low budget movie will become popular so they can buy the rights. The Amazing Prime team is hosting a Hackathon to create the algorithm and needs assistance to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.

## Results

The data preparation includes refactoring the code from this module to create one function that takes in the three files — Wikipedia data, Kaggle metadata, and the MovieLens rating data — and performs the extract, transform, load (ETL) process by adding the data to a PostgreSQL database. Insight are generated on four reports:
1. <a href="ETL_function_test.ipynb">Function Test</a>
2. <a href="ETL_clean_wiki_movies.ipynb">Clean Wiki Movies Database</a>
2. <a href="ETL_clean_kaggle_data.ipynb">Clean Kaggle Data Database</a>
2. <a href="ETL_create_database.ipynb">Create Database</a>
