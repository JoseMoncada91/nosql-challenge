Module #12 - Jose Moncada: NoSQL Establishment Analysis Challenge
Overview
In this challenge, I have been contracted by the food magazine Eat Safe, Love to assist food critics in analyzing and evaluating restaurant ratings. The goal is to extract valuable insights from data on establishments across various locations, focusing on hygiene scores and geographical factors.

The challenge is divided into three parts: Database Setup, Database Update, and Exploratory Analysis. Each part builds upon the last, helping us to organize, update, and explore the restaurant data effectively.

Part 1: Database Setup
In this section, we set up the environment and load the restaurant data into a MongoDB database. Here, we:

Import the restaurant data from a provided JSON file into MongoDB.
Set up the necessary libraries (like PyMongo) to interact with the database.
Create a MongoClient instance to establish a connection.
Verify the setup by checking the contents of the database and preparing the collection for further use.

Part 2: Database Update
Here, we update the database with new information:

Add a new establishment, Penang Flavours, which is located in Greenwich but hasn't been rated yet. This new restaurant is added to the database with relevant fields such as business name, type, location, and more.
Find and assign the appropriate BusinessTypeID to the new restaurant based on its type.
Remove any establishments from the database that fall within the Dover Local Authority, as the magazine is not interested in them.
Correct any inconsistencies in the data, such as converting number values stored as strings into numeric types.

Part 3: Exploratory Analysis
In this section, we conduct an exploratory analysis of the data:

Find establishments with a hygiene score of 20, identifying any locations with this specific rating.
Filter London-based establishments with a RatingValue of 4 or higher, which helps to pinpoint the top-rated venues.
Identify the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score, and located nearest to the newly added Penang Flavours.
Analyze hygiene scores of 0, categorizing how many establishments in each Local Authority area have this score. The results are sorted and the top ten areas are displayed.

Conclusion
This project demonstrates the power of MongoDB in organizing, updating, and analyzing large datasets. By applying queries, sorting, and filtering operations, we gain valuable insights into restaurant ratings that can assist the food magazine in making editorial decisions.

The challenge has helped develop practical skills in database management, querying NoSQL databases, and performing data analysis—all essential tools for working with large-scale data in the food industry.
