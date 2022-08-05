- What is the difference between a foreign key and a primary key?
  - Primary keys are unique while foreign keys aren't. Foreign keys are found in multiple tables.

- Where is the setup information for you database stored?
  - A special file called the "Schema" which is updated whenever changes are made to the structure of the database

- What are the important parts of a SQL command?
  - The action, the table, and the conditions

- Which SQL statement is associated with "Read" from the CRUD acronym?
  - SELECT

- Which JOIN statement keeps only the rows from both tables where they match up?
  - INNER JOIN

- How do you use an aggregate function?
  - use COUNT, SUM, AVG, MAX, and MIN with GROUP BY

- In which situation would you use the HAVING function?
  - HAVING clause is used specifically with the GROUP BY clause to filter grouped rows from the result set
  - https://www.geeksforgeeks.org/having-vs-where-clause-in-sql/
  - WHERE is used prior to GROUP BY and HAVING after GROUP BY
  - WHERE clause acts as a pre filter where as HAVING as a post filter

- Why can't I just use Ruby to process my database data?
  - SQL is faster; you might have to pull all the data out of the database then put it into memory, then iterate through the data using ruby while SQL can do it in one step