## Class Project: Expedia Hotel Recommendations

#What is the question you hope to answer?

The question that I hope to answer in this project is whether I can use Expedia customer usage behavior (such as the search they performed, how they interacted with the results, and the type of resuls returned) to predict what type of hotel the customer will ultimately book. 

This is from a past Kaggle competition (https://www.kaggle.com/c/expedia-hotel-recommendations), and the goal of the competition is stated as "to predict the booking outcome (hotel cluster) for a user event, based on their search and other attributes associated with that user event"

#What data are you planning to use to answer that question?
The data is provided as part of the Kaggle competition. It consists of a "destinations.csv" file which provides descriptive data about destinations the user is searching for, and training/testing data which provides information about the users' interaction with 

#What do you know about the data so far?

* Everything is provided via CSV files
* I know that I will likely need to "join" data between the two files
* The customer activity includes both click events and booking events
* The training data apparently has a "leakage" issue; I don't know what the offending column is, but I think it will be interesting to try to find out
* The destination hotels are organized into "clusters", but hotels can move in/out of clusters based on seasonality

#Why did you choose this topic?
* I chose this topic because of it's relation to e-commerce, and my interest in applying data science to problems in that field. This felt pretty close to the type of problem I could solve in my current role
* I also chose this topic because I felt that I would have at least some sense of "domain knowledge" that might help me understand the data and the user behavior better.
