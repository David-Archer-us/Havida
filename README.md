# Havida: Millions of Books

## This is a term project for building a book recommendation system based on book ratings and user data. We used data from “Goodreads” on https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home, mainly goodreads_books.json.gz and goodreads_interactions.csv

## This recommendation system will accept userID, title, and/or genre as inputs and recommend a book for the user.

## book_final.ipynb is the final solution. It also added checking the recommendation is not already read. This solution's rmse = 0.83. It can be done on a ram>256G gpu in 5 hours with Jupyter Notebook, Python3.8+.

## Some major libraries used for the final solution are pandas, surprise.

## We also tried some other approaches on TensorFlow, Spotlight and got some interesting results. tensorflow_models.ipynb and 256GroupProject_Spotlight.ipynb can be directly run on jupyter notebook with Python3.8+.

## We developed a generic book recommender system for anonymous users. Books_EDA.ipynb can be directly run on jupyter notebook with Python3.8+ as well.


