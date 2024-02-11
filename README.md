# Codecademy Learners Mockup Data



## Overview

This project aims to utilize SQL skills to analyze mockup data of Codecademy learners. The dataset comprises two tables: `users` and `progress`. The project entails extracting insights from the data using SQL queries and aggregate functions.



## Project Goals

- Utilize SQL knowledge to analyze Codecademy learners' data.

- Perform various queries and aggregate functions to extract insights.

- Explore patterns and trends within the dataset.



## Table Structures

- **users table**:

 - user_id

 - email_domain

 - country

 - postal

 - mobile_app

 - sign_up_at (DATETIME)

  

- **progress table**:

 - user_id

 - learn_cpp

 - learn_sql

 - learn_html

 - learn_javascript

 - learn_java



## Tasks

- [ ] Familiarize with the data using `SELECT *` from both tables.

- [ ] Identify the top 25 schools (.edu domains).

- [ ] Determine the number of .edu learners located in New York.

- [ ] Count the Codecademy learners using the mobile app.

- [ ] Use the `strftime()` function to analyze sign-up counts for each hour.

- [ ] Join the two tables and explore further insights:

 - [ ] Identify preferred courses among different schools.

 - [ ] Analyze courses taken by students from New York.

 - [ ] Analyze courses taken by students from Chicago.



## Development

- **Language**: SQL

- **Tools**: SQLite, DB Browser



## Resources

- [SQLite Setup Guide](https://www.codecademy.com/article/what-is-sqlite)
- [DB Browser](https://www.codecademy.com/article/setting-up-db-browser)
