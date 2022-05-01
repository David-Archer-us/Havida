# Havida: Millions of Books

## This is a term project for building a book recommendation system based on book ratings and user data. We use data from “Goodreads” on https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home, mainly goodreads_books.json.gz and goodreads_interactions.csv

## This recommendation system will accept userID, title, and/or genre as inputs and recommend a book for the user.

## book_final.ipynb is the final solution that fixed the rmse>1.9 problem in previous solutions by removing the zero ratings from the dataset. It also added checking the recommendation is not already read. This solution's rmse = 0.97. It can be done on a ram>256G gpu in 5 hours with Jupyter Notebook, Python3.8+.

## Some major libraries used are pandas, surprise
