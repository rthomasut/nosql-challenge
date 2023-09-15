# NoSQL Challenge

## Description
This project involves working with NoSQL data using MongoDB and Python. The goal is to analyze food hygiene ratings data in the United Kingdom and make necessary updates to the database as well as perform exploratory analysis.

## Part 1: Database and Jupyter Notebook Set Up
- Created a MongoDB database named 'uk_food'.
- Imported data from the 'establishments.json' file into the 'establishments' collection.
- Confirmed the database and collection were created successfully.
- Displayed one document from the 'establishments' collection.

## Part 2: Update the Database
- Added information for a new halal restaurant, "Penang Flavours," to the database.
- Found and updated the BusinessTypeID for "Restaurant/Cafe/Canteen."
- Removed establishments in the Dover Local Authority from the database.
- Converted latitude, longitude, and RatingValue to appropriate data types.

## Part 3: Exploratory Analysis
### Question 1
- Found establishments with a hygiene score equal to 20.

### Question 2
- Identified establishments in London with a RatingValue greater than or equal to 4.

### Question 3
- Found the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to "Penang Flavours."

### Question 4
- Determined the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest. Printed the top ten local authority areas.
