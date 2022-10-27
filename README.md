# Book-Recommendation-Engine-using-KNN
FCC Challenge

# Problem Desription

Problem description Content is copied from FCC Google Colab link:

https://colab.research.google.com/github/freeCodeCamp/boilerplate-book-recommendation-engine/blob/master/fcc_book_recommendation_knn.ipynb

In this challenge, you will create a book recommendation algorithm using K-Nearest Neighbors.

You will use the Book-Crossings dataset. This dataset contains 1.1 million ratings (scale of 1-10) of 270,000 books by 90,000 users.

After importing and cleaning the data, use NearestNeighbors from sklearn.neighbors to develop a model that shows books that are similar to a given book. The Nearest Neighbors algorithm measures distance to determine the “closeness” of instances.

Create a function named get_recommends that takes a book title (from the dataset) as an argument and returns a list of 5 similar books with their distances from the book argument.
