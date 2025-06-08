# nosql-challenge
module 12

# Instructions
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# Part 1: Database and Jupyter Notebook Setup
- Connected to MongoDB using PyMongo
- Verified successful data import and confirmed the creation of the uk_food database and establishments collection
- Displayed a sample document using find_one() and pprint()

# Part 2: Database Updates
- Inserted a new halal restaurant, Penang Flavours, into the collection
- Located and updated its BusinessTypeID
- Removed all records where LocalAuthorityName was "Dover"
- Converted fields (latitude, longitude, RatingValue) from strings to correct numerical types

# Part 3: Exploratory Analysis
Using PyMongo and Pandas:
- Identified establishments with a hygiene score of 20
- Queried London establishments with a RatingValue of 4 or higher
- Found the top 5 establishments near Penang Flavours with RatingValue 5 and lowest hygiene scores
- Aggregated and ranked local authorities by the number of establishments with a hygiene score of 0
