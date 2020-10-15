# Big Data
UC Berkeley Extension Data Analytics Boot Camp Module 16

---

This assignment was done and submitted on Google Colaboratory. The link to my Colab workbook for the module files is [here](https://colab.research.google.com/drive/17uht8ZHqXJov6voWhfsfUFJCSb-fy3T0?usp=sharing).

The link to the challenge assignment workbook is [here](https://colab.research.google.com/drive/1xFXA77m_LkfspLMxnvbwKD8ByIY0aOR7?usp=sharing).

### Objectives:

In this assignment, we were tasked with running the ETL process on the cloud, using Spark. We utilized PySpark to run statistical analysis on a database of US-based Amazon.com reviews for cameras. 

We first created our tables in the RDS database. We then extracted the data from the S3 bucket and loaded it into a dataframe. Once the data was in a DataFrame, we transformed it to fit the desired schema (from schema.sql). To complete the ETL process, we loaded the DataFrames that correspond to tables into an RDS instance.

Once the ETL process was completed, we performed statistical analyses in PySpark to determine if the Vine reviews were unbiased.

