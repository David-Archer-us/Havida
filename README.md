# Havida: Infinite Books

## This is a term project for building a book recommendation system based on book ratings and user data. We use data from “Goodreads” on https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home, mainly goodreads_books.json.gz and goodreads_interactions.csv

## This recommendation system will accept userID, title, and/or genre as inputs and recommend a book for the user.

## book_final_1.ipynb is the final solution that fixed the rmse>1.9 problem in other solutions by removing the zero ratings from the dataset. This solution's rmse = 0.97. It can be done on a ram>256G gpu in 5 hours with Jupyter Notebook, Python3.8+.

## recommendation_on_sampled_data.ipynb and book_sampled_two_models.ipnb are experimental solutions. They could be run on the Jupyter Notebook with Python 3.8+, required ram>256G gpu

## 'Book recommendation system using surprise.ipynb' is used as a template with some bugs.

## Some major libraries used are pandas, surprise
