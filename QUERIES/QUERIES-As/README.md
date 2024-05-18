link

https://www.codecademy.com/courses/intro-to-sql/lessons/queries/exercises/alias-as


### QUERIES

#### As

Knowing how SELECT works, suppose we have the code below:
```
SELECT name AS 'Titles'
FROM movies;
```
Can you guess what AS does?

AS is a keyword in SQL that allows you to rename a column or table using an alias. The new name can be anything you want as long as you put it inside of single quotes. Here we renamed the name column as Titles.

Some important things to note:

- Although it’s not always necessary, it is considered best practice to surround your aliases with single quotes.
 - Note that this practice is specific to SQLite, the RDBMS used in this exercise. When you work with other RDBMSs, notably PostgreSQL, no quotes or double quotes may be required in place of single quotes.
- When using AS, the columns are not being renamed in the table. The aliases only appear in the result.


### Instructions
Checkpoint 1 Passed
1. To showcase what the AS keyword does, select the name column and rename it with an alias of your choosing.

Place the alias inside single quotes, like so:
```
SELECT name AS '______'
FROM movies;
```

Note in the result, that the name of the column is now your alias.

Hint

Suppose you want to rename the name column as Binge, then the query would look like:
```
SELECT name AS 'Binge' 
FROM movies;
```
If this is your query, then the name of the column in the result would be Binge.

The underscores are only there for directional purposes.

2. Edit the query so that instead of selecting and renaming the name column, select the imdb_rating column and rename it as IMDb.

The AS syntax is as follows:
```
SELECT column AS 'Nickname' 
FROM table_name;
```
To rename the imdb_rating to IMDb:
```
SELECT imdb_rating AS 'IMDb' 
FROM movies;
```
Put single quotes around the alias.
SQL commands end with a ;.
