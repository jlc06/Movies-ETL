# Amazing Prime Movies ETL Database

## Purpose

In preparation for a hackaton sponsored by Amazing Prime, Britta and I are tasked with extracting data from Wikipedia and MovieLens, transforming the data, and loading it into a SQL database to be used by the participants. After our initial process is complete and the database is created, Amazing Prime let us know how much it loves the dataset and wants to keep it updated on a daily basis. Britta and I then got to work creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into our existing tables. In the end, we successfully refactored our initial code  to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
