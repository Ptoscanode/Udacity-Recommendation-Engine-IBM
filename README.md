# Udacity-Recommendation-Engine-IBM

## Project Motivation

For this project we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like.

The project divided into the following tasks:

I. Exploratory Data Analysis

Before making recommendations of any kind, we will need to explore the data for the project. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook.

II. Rank Based Recommendations

To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, we might come up with some extremely creative ways to develop a content based recommendation system. 

V. Matrix Factorization

Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with. Then, we will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.


## Requirements

This project requires Python 3.x and the following Python libraries installed

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](http://matplotlib.org/)


## Files in the repository

`Recommendations_with_IBM.ipynb`: Jupyter notebook containing the analysis of the project

`Recommendations_with_IBM.html`: HTML version of the Jupyter notebook

### Folder data

`articles_community.csv`: CSV file containing articles and the details of how users interacted with them

`user-item-interactions`: CSV file with more content abour the articles

### Folder libraries

`project_tests_new.py`: library containing functions to be executed in the notebook


## Results
Results and discussions about next steps can be found in `Recommendations_with_IBM.ipynb`


## Acknowledgements

https://towardsdatascience.com/introduction-to-recommender-systems-1-971bd274f421

https://en.wikipedia.org/wiki/Knowledge-based_recommender_system

https://www.analyticsvidhya.com/blog/2015/08/beginners-guide-learn-content-based-recommender-systems

https://en.wikipedia.org/wiki/Collaborative_filtering

https://en.wikipedia.org/wiki/Matrix_factorization_(recommender_systems)
