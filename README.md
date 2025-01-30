# nosql-challenge
Module 12 Challenge

## README for NoSQL Challenge


# Introduction
The UK Food Standards Agency assigns food hygiene ratings to establishments across the UK. You’ve been hired by Eat Safe, Love magazine to analyze this data and provide insights for their food critics.

# Instructions
# Part 1: Database Setup
- Import Data

Use NoSQL_setup_starter.ipynb to import the establishments.json file into MongoDB.
Create a database uk_food and a collection establishments.

- Verify Setup

List databases and collections to confirm uk_food and establishments exist.
Use find_one() to display one document from establishments.

# Part 2: Database Updates
- Add New Restaurant

Add Penang Flavours to the database with the provided details.
- Find and Update BusinessTypeID

Query for BusinessTypeID of "Restaurant/Cafe/Canteen" and update Penang Flavours.
- Remove Dover Establishments

Remove establishments in Dover and verify the deletion.
- Convert Strings to Numbers

Use update_many() to convert latitude, longitude, and RatingValue to the correct numeric types.

# Part 3: Exploratory Analysis
- Hygiene Score = 20

Find establishments with a hygiene score of 20 and display the results.

- London Establishments with Rating ≥ 4

Query establishments in London with a RatingValue of 4 or higher.
- Top 5 Rating 5, Nearest to Penang Flavours

Find the top 5 establishments with a RatingValue of 5, sorted by hygiene score and proximity to Penang Flavours.
- Local Authorities with Hygiene Score 0

Use aggregation to count establishments in each Local Authority with a hygiene score of 0 and sort by count.

# Technologies Used
Database: MongoDB
Programming Language: Python
Libraries: PyMongo, pprint
Tools: Jupyter Notebook