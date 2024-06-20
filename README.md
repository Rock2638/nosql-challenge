# nosql-challenge
The UK Food Standards Agency evaluates various establishments across the United Kingdom and gives them a food hygiene rating. In this challenge, I assist the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

Part 1: Database and Jupyter Notebook Set Up
For this section of the challenge:

NoSQL_setup_starter.ipynb was used.
The data provided in the establishments.jsonfile was imported and the database was named uk_food and the collection was named establishments.
The libraries PyMongo and Pretty Print (pprint) were imported within my notebook.
An instance of the Mongo Client was created, and the data was loaded properly.
The establishments collection was assigned to a variable in preparation for use.
Part 2: Update the Database
Using NoSQL_setup_starter.ipynb, changes/modifications were made to the establishments collection and information about an exciting new halal restaurant in Greenwich, was added to the database:

Part 3: Exploratory Analysis
The editors of a food magazine Eat Safe, Love had specific questions they wanted answered, to help them find the locations they wished to visit and avoid.
NoSQL_analysis_starter.ipynb was used for this section of the challenge. After exploring the database, the answers to the following questions were found and provided to the magazine editors:

Which establishments have a hygiene score equal to 20?
Which establishments in London have a RatingValue greater than or equal to 4?
What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, “Penang Flavours”?
How many establishments in each Local Authority area have a hygiene score of 0? Sorting the results from highest to lowest and printing out the top ten local authority areas.
