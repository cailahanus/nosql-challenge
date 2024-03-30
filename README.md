# nosql-challenge

## Repository Summary

# Part 1: Database and Jupyter Notebook Set Up
- Import the establishments data provided in the establishments.json file into a MongoDB database named uk_food, and create a collection named establishments.
- Confirm that the database and collection are created properly by listing the databases and collections, and display one document from the establishments collection.
- Assign the establishments collection to a variable for further use.

# Part 2: Update the Database
- Add a new restaurant named "Penang Flavours" to the database with specific details.
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the new restaurant with the found BusinessTypeID.
- Check and remove any establishments within the Dover Local Authority from the database.
- Convert certain number values stored as strings to decimal and integer numbers using update_many.

# Part 3: Exploratory Analysis
- Answer specific questions about the data using MongoDB queries and aggregation:
- Identify establishments with a hygiene score equal to 20.
- Find establishments in London with a RatingValue greater than or equal to 4.
- Determine the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score and nearest to "Penang Flavours".
- Count the number of establishments with a hygiene score of 0 in each Local Authority area, sort the results, and display the top ten local authority areas.
- Each question involves querying the database, displaying the number of documents, displaying the first document, converting the result to a Pandas DataFrame, printing the number of rows in the DataFrame, and displaying the first 10 rows.
