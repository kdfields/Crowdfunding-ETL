# Crowdfunding-ETL

## Project Overview
Perform the ETL (Extract, Transform, and Load) process on a crowdfunding dataset that contains information on backers who made pledges to fund independent projects or ventures.  The data will be migrated from an Excel data file into a PostgreSQL database.  During that process Python will be used to extract and transform the data, and SQL will be used to load and query the data.

### Resources
+ backer_info.csv
+ Python 3.7.6, SQL, PostgreSQL, ERD

## Summary
Using Python, Pandas, Jupyter Notebook, and PostgreSQL database:
+ Extracted and transformed data from a large Excel file into smaller .csv files
+ Created a PostgreSQL database and tables using an ERD
+ Loaded the .csv files into a datbase
+ Query the data to retrieve data and generate reports


## Images
Python was used to transform a "dirty" .csv file into a "clean" Pandas dataframe.

**Dirty data:**

![image](https://user-images.githubusercontent.com/113741694/233163073-76f305f7-001f-4c2f-851d-9f2aa77d1221.png)

**Clean data:**

![image](https://user-images.githubusercontent.com/113741694/233163283-ca3a69a7-eec3-417c-b735-6934d0109c99.png)

Mapped the connections between the .csv files to prepare before loading the data into PostgreSQL:

![image](https://user-images.githubusercontent.com/113741694/233164224-25e6d05d-dd5e-47bd-831b-1f7de4b79eca.png)

Queried the data for reporting to stakeholders:

![image](https://user-images.githubusercontent.com/113741694/233164906-0585114f-6142-404d-b7b7-1bc83486f297.png)








