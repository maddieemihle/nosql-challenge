# noSQL Challenge: Eat Safe, Love

## Background 
The UK Food Standards Agency evaluates various establishments across the United Kingdom and gives them a food hygiene rating. We were contracted by a food magazine _Eat Safe, Love_ to evaluate some of the rating data in order to help their journalists and food critics decide where to focus future articles. 

In this challenge, skills continually learned in Pandas, Python, Jupyter and noSQL to evaluate the data given. 

## Challenge 
### Part 1: Database Setup 
Data was imported from the given JSON files from Terminal. The libraries were imported and using MongoDB on the starter notebook named _NoSQL_setup_starter.ipynb_. Then, the dependencies, database, and collections were established. 

### Part 2: Update the Database 
Using the same starter notebook, modifications were made to the database so I was able to perform all queries and analyses for _Eat Safe, Love_. A new restaurant was added named "Penang Flavours,” and it was updated with the BusinessID found. The magazine was not interested in any restaurants in Dover, so these were checked for, returned, and then deleted. Lastly, some number values were stored as strings, when they should've been stored as numbers. Longitude and Latitude were converted to decimal numbers, and RatingValue was converted to integer numbers. 

### Part 3: Exploratory Analysis 
_Eat Safe, Love_ gave specific questions that they wanted answered to help them find the locations that they wished to visit and avoid. Using the _NoSQL_analysis_starter.ipynb_ for this section of the challenge, several questions were answered to determine: 
1. Which establishments have a hygiene score equal to 20? 
2. Which establishments have a RatingValue greater than or equal to 4? 
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Results 
In Part 3 of the challenge, several questions were asked and answered. 

1. Which establishments have a hygiene score equal to 20? 
* The number of establishments that have a hygiene score equal to 20 are 41 from the 'uk_food' dataset.

2. Which establishments have a RatingValue greater than or equal to 4? 
* The establishments that have a RatingValue greater than or equal to 4 is 34.

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
* The top five establishments with a RatingValue of 5 (and sorted from lowest to nearest the resturant Penang Flavours) are: "Volunteer", "Plumstead Manor Nursery", "Atlantic Fish Bar", "Iceland", and "Howe and Co Fish and Chips-Van 17"

4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
* The number of establishments in each Local Authority area that have a hygiene score of 0 is 55. 

## Methods Used 
* Pandas 
* Python 
* noSQL 
* JSON 

## Software Used 
* MongoDB 
* MongoDB Compass 
* Visual Studio Code 

## References 
UK Food Standards Agency. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0 
