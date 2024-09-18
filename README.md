# nosql-challenge
Module 12

This challenge was focusing on PyMongo using the Jupyter Notebook. 

Part 1:

Importing the dataset from the MongoDB using the following code: ` mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`. Renaming my database to a variable, and assigning it to a collection. 

Part 2:
After creating the data collection, there were updates like adding a new restaurant, updating 
the business type id, finding and deleting information that was no longer needed, and finally updating data types from string to integer.

Part 3:
Using "count_documents" to identify the hygiene score for establishments that had a score equal to 20. Creating queries for establishments with certain criteria based of off hygiene, ratings, and location. Transforming the results to a pandas DataFrame and showing the first 10 rows to each question.

