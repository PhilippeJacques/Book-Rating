## BOOK’S RATING : train a model that predicts a book’s rating.

### Table of Contents

1. [Project Purpose](#projet)
2. [Installation](#install)
3. [Files Descriptions](#files)
4. [Authors and motivations](#authors)



### What is the project ? <a name="projet"></a>

The purpose of this project is to train a model that predicts a book’s rating using the provided dataset. 

The dataset provided is a curation of Goodreads books based on real user information.


### Installation <a name="install"></a>

To explore this project download the dataset from Goodreads (books.csv) and the last python notebooks (PhilippeBookPredVersion6-1.ipynb).

All dependencies to install are listed in requirements.txt file. 


### Files Descriptions <a name="files"></a>

 * books.csv : 
        "bookID" A unique identification number for each book.
        "title" The name under which the book was published.
        "authors" The names of the authors of the book. Multiple authors are delimited by “/”.
        "average_rating" The average rating of the book received in total.
        "isbn" Another unique number to identify the book, known as the International Standard Book Number.
        "isbn13" A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
        "language_code" Indicates the primary language of the book. For instance, “eng” is standard for English.
        "num_pages" The number of pages the book contains.
        "ratings_count" The total number of ratings the book received.
        "text_reviews_count" The total number of written text reviews the book received.
        "publication_date" The date the book was published
        "publisher" The name of the book publisher.
    
 * PhilippeBookPredVersion6-1.ipynb : 
        This notebook conducts data analysis tasks such as data processing, cleaning, and exploratory analysis, accompanied by the creation of illustrative plots. It proceeds with feature selection through engineering and pruning, offering clear justifications for the chosen features. The subsequent steps involve model training, elucidating the reasoning behind the chosen model while also comparing different model variations. Ultimately, comprehensive evaluations are executed using suitable metrics, with a subsequent interpretation of results to facilitate well-informed decisions.

### Authors & Motivations <a name="authors"></a>

This project was carried out as part of the preparation for an MSC in Data Science and Data Engineering at the DSTI.

The members of the project group are :
 - Philippe FOGOUM - Data engineering
 - Saïd HAMDI - Data science
 - David BEGARIN - Data science
 - Guillaume NONY - Data science
