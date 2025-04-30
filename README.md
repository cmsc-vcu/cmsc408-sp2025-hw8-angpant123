# cmsc408-sp2025-hw8

Homework 8 - World Bank Indicator Analysis

# Overview of the Pipeline
The loader.qmd document performs the following steps:

Downloads source data in ZIP format from the World Bank Data Store.
Unzips the required CSV files needed for analysis.
Loads the extracted CSVs into MySQL using Pandas and SQLAlchemy.
Sets permissions for users to access the loaded tables.


# How to Run
Prerequisites
Ensure the following Python packages are installed:

pandas
sqlalchemy
python-dotenv
mysql-connector-python or equivalent MySQL client

You can install them with:

pip install pandas sqlalchemy python-dotenv mysql-connector-python

