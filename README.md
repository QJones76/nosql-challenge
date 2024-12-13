# NoSQL Database Challenge using MongoDB
In this challenge I used [MongoDB](https://www.mongodb.com/), a non-relational database management system, along with [PyMongo](https://pypi.org/project/pymongo/), python's interface for MongoDB, to import a database and perform some basic analysis on the collection within that dataset. 

## How to Use
Follow the NoSQL_database_setup file to import the same database into your own system. Then, after importing the database, you can follow the file further to understand basic database manipulation code snippets. After you have finished with the NoSQL_database_setup file, you can perform your own analysis, or you can look into the NoSQL_analysis file to help understand PyMongo's more complex database manipulation processes. 

### Note on the Data
While the 'RatingValue' goes from 1 to 5, with 5 being the best, the 'scores' section of the data is inverse.

## My Analysis
With a simple analysis of the establishments contained in the dataset, I was able to find:
- There were 41 total establishments with the worst hygiene score possible
- There were 33 establishments in London that had a rating of 4 or higher
- I was able to find 5 nearby establishments of a fictional restaurant with lowest Hygiene score, a score of 0 being the lowest
- The top five local authorities with the most establishments having the hygiene score equal to 0, which is the best score available, were:
  - Thanet with 1130 establishments
  - Greenwhich with 882 establishments
  - Maidstone with 713 establishments
  - Newham with 711 establishments
  - Swale with 686 establishments
