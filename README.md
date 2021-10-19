# movies-ETL

## OVERVIEW

In this project, an automated **ETL**<sup>1</sup> pipeline was created to read, clean, condense, and load various data into an existing postgreSQL database.

Raw was sourced from the following locations: files scraped from Wikipedia, Kaggle metadata, and MovieLens rating data. The data was extracted using Python, cleaned and formatted using the Pandas library, and then stored in a PostgreSQL database.


[1] *Extract, transform, load*

## **TOOLS**

### SOFTWARE

* Python 3.9.3
  * Anaconda Navigator 2.0.3
  * Conda 4.10.3   
* Jupyter Notebook 6.3.0 
* PostgreSQL 14.0
* pgAdmin 4


## RESULTS

### CODE

[Deliverable 1](https://github.com/farwaali08/movies-ETL/blob/a21faa3f31ea0f9fddccd18c5a5868764e21637f/ETL_function_test.ipynb)

[Deliverable 2](https://github.com/farwaali08/movies-ETL/blob/a21faa3f31ea0f9fddccd18c5a5868764e21637f/ETL_clean_wiki_movies.ipynb)

[Deliverable 3](https://github.com/farwaali08/movies-ETL/blob/a21faa3f31ea0f9fddccd18c5a5868764e21637f/ETL_clean_kaggle_data.ipynb)

[Deliverable 4](https://github.com/farwaali08/movies-ETL/blob/a21faa3f31ea0f9fddccd18c5a5868764e21637f/ETL_create_database.ipynb)



Below are screenshots of the files that were loaded into the database. These can also be found in the "Resources" folder.

### **Movies**
![alt_text](https://github.com/farwaali08/movies-ETL/blob/f1d0fecffc9c134922e91a01d073ffb8e4b818c7/Resources/movies_query.png)

### **Ratings**
![alt_text](https://github.com/farwaali08/movies-ETL/blob/f1d0fecffc9c134922e91a01d073ffb8e4b818c7/Resources/ratings_query.png)
