# movies-ETL

## OVERVIEW

In this project, an automated **ETL**<sup>1</sup> pipeline was created to read, clean, condense, and load various data into an existing postgreSQL database.

Raw was sourced from the following locations: files scraped from Wikipedia, Kaggle metadata, and MovieLens rating data. The data was extracted using Python, cleaned and formatted using the Pandas library, and then stored in a PostgreSQL database.


[1] *Extract, transform, load*

## **TOOLS**

### Software

* Python 3.9.3
  * Anaconda Navigator 2.0.3
  * Conda 4.10.3   
* Jupyter Notebook 6.3.0 
* PostgreSQL 14.0
* pgAdmin 4


## RESULTS

Below are screenshots of the files being loaded in to the database. These can also be found in the "Resources" folder.

### **Movies**
![alt_text](https://github.com/farwaali08/movies-ETL/blob/f1d0fecffc9c134922e91a01d073ffb8e4b818c7/Resources/movies_query.png)

### **Ratings**
![alt_text](https://github.com/farwaali08/movies-ETL/blob/f1d0fecffc9c134922e91a01d073ffb8e4b818c7/Resources/ratings_query.png)
