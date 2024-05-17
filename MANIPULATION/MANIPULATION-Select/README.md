link to lesson

https://www.codecademy.com/courses/intro-to-sql/lessons/manipulation/exercises/select
https://www.codecademy.com/paths/design-databases-with-postgresql/tracks/what-is-a-database/modules/working-with-your-first-database/lessons/manipulation/exercises/select

# MANIPULATION

### Select

[SELECT](https://www.codecademy.com/resources/docs/sql/commands/select?page_ref=catalog) statements are used to fetch data from a database. In the statement below, SELECT returns all data in the name column of the celebs table.
```
SELECT name FROM celebs;
```
1. SELECT is a clause that indicates that the statement is a query. You will use SELECT every time you query data from a database.
2. name specifies the column to query data from.
3. FROM celebs specifies the name of the table to query data from. In this statement, data is queried from the celebs table.

You can also query data from all columns in a table with SELECT.
```
SELECT * FROM celebs;
```
* is a special wildcard character that we have been using. It allows you to select every column in a table without having to name each one individually. Here, the result set contains every column in the celebs table.

SELECT statements always return a new table called the result set.


### Instructions
Checkpoint 1 Passed
1. Let’s take a closer look at SELECT and retrieve all the names in the celebs table. In the code editor, type:
```
SELECT name FROM celebs; 

```

Hint

Don’t forget to include the FROM clause and the name of the table which we are selecting the data from!

The result should only have a single column (name).


2. Delete your previous SELECT statement from the code editor.

To SELECT all the data in the celebs table, enter the following statement in the code editor using the * wildcard character:
```
SELECT * FROM celebs;
```

Hint

Did you delete the first SELECT statement from the code editor?


