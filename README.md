#### NoSQL_Challenge
#### Eat Safe, Love

## Description
In this challenge, I was asked to analyze and explore restaurant food hygiene data in the UK. According to the challenge instructions, “the UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles”.

Question 1: Which establishments have a hygiene score equal to 20? None.

Question 2: Which establishments in London have a RatingValue greater than or equal to 4? Charlie’s, Mv City Cruises Erasmus, Benfleet Motor Yacht Club, Tilbury Seafarers Centre, Coombs Catering t/a The Lock and Key, Mv Valulla, Tereza Joanne, Brick Lane Brews, WH Smith, The Nuance Group Limited

Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"? 

Empty DataFrame
Columns: []
Index: []


Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas. Number of establishments with hygiene score 0 in each Local Authority:

[{'_id': 'Newham', 'count': 13},
 {'_id': 'Waltham Forest', 'count': 9},
 {'_id': 'Greenwich', 'count': 7},
 {'_id': 'Uttlesford', 'count': 6},
 {'_id': 'Barking and Dagenham', 'count': 4},
 {'_id': 'Redbridge', 'count': 4},
 {'_id': 'Southend-On-Sea', 'count': 3},
 {'_id': 'Tendring', 'count': 3},
 {'_id': 'Rochford', 'count': 2},
 {'_id': 'Havering', 'count': 1}]


To accomplish this analysis, I utilized my Mac OS, Jupyter Notebook, PyMongo, Pandas, Matplotlib, and GitHub.

## Table of Contents
Code for analysis found in the “NoSQL_analysis_starter.ipynb” and “NoSQL_setup_starter.ipynb” files within the main directory on my github "nosql_challenge" repo. Data for analysis was compiled into the 'establishments.json' located in the ‘Resources’ directory.

## Installation Instructions
Code utilized for this challenge can be found in the files within the main directory on my github "nosql_challenge" repo.

## Usage
Can Git Clone all files from my 'nosql_challenge' repo.

## Credits
For this challenge I utilized the ASK BCS feature on Slack, Google, ChatGPT, fellow students, YouTube, Stack Overflow, TA assistance, Bootcamp tutor assistance, and educational resources related to the unit provided by the bootcamp.

## License
UK Food Standards Agency
Links to an external site.
 (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB
Links to an external site.
. Contains public sector information licensed under the Open Government Licence v3.0
Links to an external site.

Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

