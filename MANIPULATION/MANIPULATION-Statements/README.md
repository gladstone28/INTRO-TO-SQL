link to lessone
https://www.codecademy.com/paths/design-databases-with-postgresql/tracks/what-is-a-database/modules/working-with-your-first-database/lessons/manipulation/exercises/statements


MANIPULATION
Statements
4 min
The code below is a SQL statement. A statement is text that the database recognizes as a valid command. Statements always end in a semicolon ;

```
CREATE TABLE table_name (
   column_1 data_type, 
   column_2 data_type, 
   column_3 data_type
);


```

Let’s break down the components of a statement:

1. CREATE TABLE is a clause. Clauses perform specific tasks in SQL. By convention, clauses are written in capital letters. Clauses can also be referred to as commands.
2. table_name refers to the name of the table that the command is applied to.
3. (column_1 data_type, column_2 data_type, column_3 data_type) is a parameter. A parameter is a list of columns, data types, or values that are passed to a clause as an argument. Here, the parameter is a list of column names and the associated data type.
The structure of SQL statements vary. The number of lines used does not matter. A statement can be written all on one line, or split up across multiple lines if it makes it easier to read. In this course, you will become familiar with the structure of common statements.


### Instructions
Checkpoint 1 Passed
1.Let’s take a closer look at the statement we wrote before. In the code editor, type:
```
SELECT * FROM celebs;
```
Run the code to observe the results, and ask yourself:

Which parts of the statement are the clauses?
What table are we applying the command to?
Uncover the hint to view the answers, and then proceed to the next exercise.

SELECT and FROM are the clauses here.
We are applying the command to the celebs table.
Soon you will learn more about each part of this statement!

