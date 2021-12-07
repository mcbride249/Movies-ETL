# Movies-ETL

## Project Overview

Extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database that will allow Amazing Prime to conduct a hackathon to develop an algorithm that will predict which low budget movies will become popular.

**Goals:**

1. Extract the Wikipedia Movies JSON and the Kaggle Data.
2. Clean the Wikpedia, Kaggle and Ratings data and merge the metadata.
3. Create a database and load the data into it.
     

**##Summary**

1. Extract the Wikipedia Movies JSON and the Kaggle Data.

2. Clean the Wikpedia, Kaggle and Ratings data and merge the metadata.

3. Create a database and load the data into it.




**##Resources**
-Data Source: movies_metadata.csv, ratings.csv, wikipedia-movies.json
-Software: Python 3.7.10, Visual Studio Code, 1.38.1, pgAdmin 4v6


**##Module 8 - Challenge** 

**##Purpose##**

The purpose of this challenge was to extract and transform real world movie data sets from Wikipedia and Kaggle and then merge them before loading them into a database. The method for this required one to improt the Wikipedia data using its JSON file and importing the data from Kaggle using the movies_metadata.csv and ratings.csv files provided on its website. The data provided in these documents would be "cleaned" by filtering and refining the data to only relevant the relevant information that we decided should be included in our own hackathon dataset. This often involved removing duplicate information between the two data sets and filtering out rows that that did not contain information, as well as parsing the data based on specific criteria. In the latter parts of this process, it involved merging the two data sets from Wikipedia and Kaggle and then combining it with the ratings data. The finally step in the process involved uploading the combined movie dtaa from Wikipedia and Kaggle as well as the full ratings dataset into a movies database created on pgAdmin. 




**Deliverable 1: Write an ETL Function to Read Three Data Files **

Using your knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.


**Deliverable 1 Results**


**Deliverable 2: Extract and Transform the Wikipedia Data**

Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata.


**Deliverable 2 Results**



**Deliverable 3: Extract and Transform the Kaggle Data **

Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.


**Deliverable 3 Results**


**Deliverable 4: Create the Movie Database **

Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

**Deliverable 4 Results**
