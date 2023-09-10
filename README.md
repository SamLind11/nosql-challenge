# NoSQL Challenge
This repository contains work for the NoSQL challenge assignment for the UNC Data Analytics Bootcamp.

## Description

This project consists of two main deliverables, NoSQL_setup_starter.ipynb and NoSQL_analysis.ipynb.  I was provided a json database (establishments.json in the Resources folder) about restaurants in the UK.  The 'setup' file imports this data into a MongoDB database.  Using PyMongo, a new record is inserted into the newly created database, some records are updated, and several other records are deleted.  Additionally, some fields are updated to change their data types.

The 'analysis' file utilizes PyMongo to query the database to answer these four questions.
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

The results for these queries were then converted into Pandas Dataframes.

## Authorship

Starter code for the two Jupyter Notebook files, along with the data in establishments.json, were provided by the UNC Data Analytics Bootcamp.  The code database creation and queries was written by Sam Lind.
