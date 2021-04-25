# Movies-ETL
Perform ETL on several movie datasets to predict popular films for a streaming service.

## Summary 
Amazing Prime Videos is a platform for streaming movies and TV shows. world's largest online retailer. The Amazing prime videos team would like to develop an algorithm to predict which low-budget movies being released became popular so that they can buy the streaming rights at a bargain. To inspire the team and have some fun and connect with the local coding community Amazing Prime has decided to sponsor a Hackathon providing a clean dataset of movie data and asking participants to predict the popular pictures.

Bretta is a member of the amazing prime videos Team and she was given a task to create the datasets for the hackathon. There were two data sources. A Scrape of Wikipedia for all movies released since 1990 and rating data from the movie lines website she had to extract the data from the sources, transform it into one clean dataset, and finally load that dataset into a sql table. 

## Challenge Summary
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs our help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

