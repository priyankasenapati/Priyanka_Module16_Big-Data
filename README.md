# Priyanka_Module16_Big-Data

# Overview:

The goal of this challenge is to implement a data analytics pipeline for Review Rating Analysis - ETL processing, storing in Database and the Use SQL for Analysis.

# Scripting Languages and Tools :

Google Colab, Pyspark, Postgres, PGadmin, SQL, AWS RDS, AWS S3

# Data Sources:
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

* Used the US Mobile Apps Dataset:

https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Mobile_Apps_v1_00.tsv.gz

# Data Analytics Pipeline:

1. Perform ETL on the dataset:-

Extracted data from the S3 dataset files and loaded them into Dataframes using PySpark, Spark in Google Colab.
Transformed the dataset to clean and prep it based on the Database table  schema where it will be loaded using Spark. Loaded the data into their respective tables in the Postgres Database using JDBC APIs. The database had been previously created on Amazon RDS and the tables created on Postgres.
2. Data Analysis Using SQL
Using SQL on PgAdmin, used various queries to generate tables and counts of all the Vine (Paid) and Non Vine (Unpaid)  Review ratings.

** CONCLUSION **
   The average review rating is 3 Stars. 
   The vine_table contains only Non-Vine review ratings. Since these reviews are 
   Non-Vine reviews there isn't any way to know how trustworthy they are from this data.
 


