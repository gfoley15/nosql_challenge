# nosql_challenge

## Part 1: Database and Jupyter Notebook Set Up
- Import data from the establishments.json file into a MongoDB database named uk_food and a collection named establishments.
- Copy the import command used in the Terminal to a markdown cell in the Jupyter Notebook.

###  Library Import and Client Initialization:
- Import necessary libraries: PyMongo and Pretty Print (pprint).
- Create an instance of the Mongo Client.

### Data Confirmation:
- List the databases in MongoDB to confirm uk_food is listed.
- List the collections in the uk_food database to confirm establishments is present.
- Find one document from the establishments collection using find_one and pprint.
- Assign the establishments collection to a variable.

## Part 2: Update the Database
### Database Modification:
- Add a new restaurant, "Penang Flavours", with specific details to the establishments collection.
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update the new restaurant entry with it.
- Remove establishments within the Dover Local Authority from the database.

### Data Type Conversion:
- Convert certain number values stored as strings to decimal numbers (latitude and longitude).
- Convert RatingValue to integer numbers.

## Part 3: Exploratory Analysis
### Data Exploration:
- Identify establishments with a hygiene score equal to 20.
- Find establishments in London with a RatingValue greater than or equal to 4.
- Determine the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to "Penang Flavours".
- Count establishments in each Local Authority area with a hygiene score of 0, sorting the results from highest to lowest and displaying the top ten local authority areas.
