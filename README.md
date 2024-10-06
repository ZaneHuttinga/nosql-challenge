# nosql-challenge
Data Visualization and Analytics Boot Camp Challenge 12

## NoSQL_setup.ipynb

### Part 1
This Jupyter Notebook file contains several cells of MongoDB and PyMongo code used to set up the database 'uk_food' and add the collection 'establishments' to it.

### Part 2
The Jupyter Notebook then inserts a new document to 'establishments' for the restaurant Penang Flavours and updates it to fill in a missing piece of data.

## NoSQL_analysis

### Part 3
This Jupyter Notebook file is used to make a series of MongoDB queries to answer four questions:
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0?

Question 3 involves use of the $regex command, and Question 4 involves setting up an aggregate pipeline.