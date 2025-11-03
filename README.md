# SQL Magic in Jupyter Notebook: A Student Database Demo
This project is a simple demonstration of how to use the ipython-sql (SQL Magic) extension to interact with an SQLite database directly within a Jupyter Notebook.

## Overview
The notebook walks through the following steps:

Setup: Installing and loading the ipython-sql extension.

Database Creation: Creating an in-memory SQLite database (SQLiteMagic.db).

Table Creation: Defining and populating a table named INTERNATIONAL_STUDENT_TEST_SCORES with sample data.

Basic Querying: Running SQL SELECT queries using the %%sql magic command.

### Python Integration (Variables):

Passing a Python variable into an SQL query (e.g., where country = :country).

Assigning the result of an SQL query back to a Python variable.

Data Visualization: Converting the SQL query result into a Pandas DataFrame and using Seaborn and Matplotlib to plot a bar chart of the test score distribution.
