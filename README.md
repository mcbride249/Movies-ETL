# Movies-ETL

## Project Overview

Extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database that will allow Amazing Prime to conduct a hackathon to develop an algorithm that will predict which low budget movies will become popular.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Goals:**

1. Extract the Wikipedia Movies JSON and the Kaggle Data.
2. Clean the Wikpedia, Kaggle and Ratings data and merge the metadata.
3. Create a database and load the data into it.
     
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Summary**

1. Extract the Wikipedia Movies JSON and the Kaggle Data.

2. Clean the Wikpedia, Kaggle and Ratings data and merge the metadata.

3. Create a database and load the data into it.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Resources**
-Data Source: movies_metadata.csv, ratings.csv, wikipedia-movies.json

-Software: Python 3.7.10, Visual Studio Code, 1.38.1, pgAdmin 4v6

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Module 8 - Challenge** 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**##Purpose##**

The purpose of this challenge was to extract and transform real world movie data sets from Wikipedia and Kaggle and then merge them before loading them into a database. The method for this required one to improt the Wikipedia data using its JSON file and importing the data from Kaggle using the movies_metadata.csv and ratings.csv files provided on its website. The data provided in these documents would be "cleaned" by filtering and refining the data to only relevant the relevant information that we decided should be included in our own hackathon dataset. This often involved removing duplicate information between the two data sets and filtering out rows that that did not contain information, as well as parsing the data based on specific criteria. In the latter parts of this process, it involved merging the two data sets from Wikipedia and Kaggle and then combining it with the ratings data. The finally step in the process involved uploading the combined movie dtaa from Wikipedia and Kaggle as well as the full ratings dataset into a movies database created on pgAdmin. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 1: Write an ETL Function to Read Three Data Files **

Using your knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 1 Results**

Wikpedia Movies Dataframe:

![wiki_movies_df](https://user-images.githubusercontent.com/92111396/145039420-e3a0afc7-6024-4ea6-a579-549a98890ab2.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/Deliverable%201%20Images/wiki_movies_df.PNG


Kaggle Metadata Dataframe:

![kaggle_metadata](https://user-images.githubusercontent.com/92111396/145039630-ef44e1fa-8714-4644-890d-c9a027fb4914.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/Deliverable%201%20Images/kaggle_metadata.PNG


Ratings Dataframe:

![ratings_df](https://user-images.githubusercontent.com/92111396/145039753-da17c56e-1196-40ee-ad50-f67b87ad190a.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/Deliverable%201%20Images/ratings_df.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 2: Extract and Transform the Wikipedia Data**

Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 2 Results**

Wikipedia Movies Dataframe:

![Deliverable 2 - wiki_movies_df](https://user-images.githubusercontent.com/92111396/145040388-480992b3-4e9f-4304-b410-504078d73c79.PNG)

https://github.com/mcbride249/Movies-ETL/tree/main/Resources/Deliverable%202%20Images

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 3: Extract and Transform the Kaggle Data **

Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 3 Results**

Movies With Ratings Dataframe:

![Deliverable 3 - movies_with_ratings_df](https://user-images.githubusercontent.com/92111396/145041119-6ec1a786-927b-4223-998c-f9766e7ac7a7.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/Deliverable%203%20Images/Deliverable%203%20-%20movies_with_ratings_df.PNG


Movies Dataframe:

![Deliverable 3 - movies_df](https://user-images.githubusercontent.com/92111396/145041138-f9064539-6021-4ab8-a033-33b0b6d8101d.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/Deliverable%203%20Images/Deliverable%203%20-%20movies_df.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 4: Create the Movie Database **

Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 4 Results**

Data to Databse Runtime:

![ETL_creata_database - run time](https://user-images.githubusercontent.com/92111396/145041914-f8bf0375-4dd5-4de6-894b-478e771ece91.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/Deliverable%204%20Images/ETL_creata_database%20-%20run%20time.PNG


Movie Query:

![movies_query](https://user-images.githubusercontent.com/92111396/145041719-c76a6159-7455-4067-b21e-6a8992a6e94e.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/movies_query.PNG


Ratings Query:

![ratings_query](https://user-images.githubusercontent.com/92111396/145041712-2bedff92-f9c3-42fd-8d80-3667dd9e8865.PNG)

https://github.com/mcbride249/Movies-ETL/blob/main/Resources/ratings_query.PNG


