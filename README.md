# Movies-ETL

## Overview

The project is an introduction of the ETL (Extract, Transform and Load) process using the open-source data analysis and manipulation Pandas tool and Python. The Amazing Prime video team is excited to prepare for the hackathon. In data analysis, a hackathon is an event where teams of analysts collaborate to work intensively on a project, using data to solve a problem. Hackathons generally last several days and teams work around the clock on their projects.

Britta, a member of the Amazing Prime video team, needed to gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL database so that the hackathon participants have a nice, clean dataset to use. To do this, we followed the ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.

## Resources

  - Data Source: Wikipedia data, Kaggle metadata, and the MovieLens rating data
  - Software: Python 3.9.7, Jupyter Notebook and Pandas 1.2.4
  - Database: PostgreSQL 13

## Results

 - 6,052 Movie Data rows imported to a SQL Table in PostgreSQL
 - 26,024,289 Rating Data rows imported to a SQL Table in PostgreSQL
