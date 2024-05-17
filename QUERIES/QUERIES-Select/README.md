link

https://www.codecademy.com/courses/intro-to-sql/lessons/queries/exercises/select-ii


QUERIES
Select

Previously, we learned that SELECT is used every time you want to query data from a database and * means all columns.

Suppose we are only interested in two of the columns. We can select individual columns by their names (separated by a comma):
```
SELECT column1, column2 
FROM table_name;
```
To make it easier to read, we moved FROM to another line.

Line breaks don’t mean anything specific in SQL. We could write this entire query in one line, and it would run just fine.


### Instructions
Checkpoint 1 Passed
1. Let’s only select the name and genre columns of the table.

In the code editor, type the following:
```
SELECT name, genre 
FROM movies;

```

Hint

Instead of selecting all the columns:
```
SELECT *
FROM movies;
```
We are now just selecting the name and genre column:
```
SELECT name, genre
FROM movies;
```

Double-check your query, character by character:

- There is a comma between name and genre.
- SQL commands end with a ;.

SELECT and FROM are clauses. Clauses perform specific tasks in SQL. By convention, clauses are written in capital letters.

2. Now we want to include a third column.

Edit your query so that it returns the name, genre, and year columns of the table.

The syntax for selecting three individual columns:
```
SELECT column1, column2, column3
FROM table_name;
```

Following this format, the query below selects name, genre, and year columns (in that order) from the movies table:
```
SELECT name, genre, year
FROM movies;
```
We have to separate the column names with a comma.
SQL commands end with a ;.
