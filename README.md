NBA Sports Analytics Engine
Project Overview
This is an advanced sports analytics project that uses a PostgreSQL database to analyze NBA player statistics. The project demonstrates the creation of a powerful data analysis platform capable of calculating advanced performance metrics, identifying career patterns, and performing predictive modeling using complex SQL techniques.

Files in this Repository
File Name

Description

nba_analytics_sql.sql

The core SQL script for the project. It includes all the necessary commands to create the database tables and run a variety of analytics queries.

python_csv_fix.ipynb

A Jupyter Notebook designed to clean the Seasons_Stats.csv file by removing unnecessary columns and fixing data types, ensuring a smooth data import.

player_data.csv

The dataset containing detailed information on NBA players, including their height, weight, birth date, and college.

Players.csv

A supplementary dataset with additional player information.

Seasons_Stats.csv

The main dataset containing comprehensive player statistics for each season.

README.md

This document, providing an overview of the project and instructions for use.

How to Set Up and Run the Project
Step 1: Clean the Data
The Seasons_Stats.csv file has some formatting issues that prevent a direct import. You can use the provided Jupyter Notebook to fix this.

Ensure you have Python and the pandas library installed (pip install pandas).

Open the python_csv_fix.ipynb file in a Jupyter environment (like Jupyter Notebook, JupyterLab, or VS Code with the Jupyter extension).

Run all the cells in the notebook.

This will generate a new file, Seasons_Stats_cleaned.csv, which is a cleaned version of the original data.

Step 2: Set Up the Database
You can use the nba_analytics_sql.sql script to create your database tables in PostgreSQL.

Open PGAdmin and connect to your database.

Open the Query Tool.

Copy the entire content of nba_analytics_sql.sql into the Query Tool.

Execute the script. This will create three tables: player_data, Players, and Seasons_Stats.

Step 3: Import the Data
Now, import the cleaned CSV files into the newly created tables using PGAdmin's Import/Export tool.

In PGAdmin, right-click on each table (player_data, Players, and Seasons_Stats).

Select "Import/Export...".

For player_data:

Set Format to csv.

Set Header to Yes.

In the Columns tab, manually select the columns in the correct order: name, year_start, year_end, position, height, weight, birth_date, and college.

For Players:

Set Format to csv.

Set Header to Yes.

Manually select the columns in the correct order: player_index, player, height, weight, collage, born, birth_city, and birth_state.

For Seasons_Stats:

Set Format to csv.

Set Header to Yes.

Use the Seasons_Stats_cleaned.csv file from Step 1.

Select all the columns in the correct order as defined in the SQL script.

Step 4: Run the Analytics Queries
The nba_analytics_sql.sql file contains a variety of basic and advanced queries. You can run these queries individually in the PGAdmin Query Tool to analyze the data and explore performance metrics.

License
This project is for educational purposes and is not affiliated with the NBA. The dataset is sourced from public data.
