# Surfs-Up
Advanced data storage and retrieval HW

Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii! To help with your trip planning, you decided to do some climate analysis on the area. Because you are such an awesome person, you have decided to share your ninja analytical skills with the community by providing a climate analysis api. The following outlines what you need to do.

## Step 1 - Data Engineering
The climate data for Hawaii is provided through two CSV files. Start by using Python and Pandas to inspect the content of these files and clean the data.
- Create a Jupyter Notebook file called data_engineering.ipynb and use this to complete all of your Data Engineering tasks.

- Use Pandas to read in the measurement and station CSV files as DataFrames.

- Inspect the data for NaNs and missing values. You must decide what to do with this data.

- Save your cleaned CSV files with the prefix clean_.

## Step 2 - Database Engineering
Use SQLAlchemy to model your table schemas and create a sqlite database for your tables. You will need one table for measurements and one for stations.

- Create a Jupyter Notebook called database_engineering.ipynb and use this to complete all of your Database Engineering work.

- Use Pandas to read your cleaned measurements and stations CSV data.

- Use the engine and connection string to create a database called hawaii.sqlite.

- Use declarative_base and create ORM classes for each table.

-   You will need a class for Measurement and for Station.

-   Make sure to define your primary keys.

- Once you have your ORM classes defined, create the tables in the database using create_all.
