link 

https://www.codecademy.com/courses/intro-to-sql/lessons/manipulation/exercises/update


### MANIPULATION

## Update

The UPDATE statement edits a row in a table. You can use the UPDATE statement when you want to change existing records. The statement below updates the record with an id value of 4 to have the twitter_handle @taylorswift13.
```
UPDATE celebs 
SET twitter_handle = '@taylorswift13' 
WHERE id = 4; 
```
1. UPDATE is a clause that edits a row in the table.
2. celebs is the name of the table.
3. SET is a clause that indicates the column to edit.

twitter_handle is the name of the column that is going to be updated
@taylorswift13 is the new value that is going to be inserted into the twitter_handle column.
4. WHERE is a clause that indicates which row(s) to update with the new column value. Here the row with a 4 in the id column is the row that will have the twitter_handle updated to @taylorswift13.


### Instructions
Checkpoint 1 Passed
1. Update the table to include Taylor Swift’s twitter handle. In the code editor, type:
```
UPDATE celebs 
SET twitter_handle = '@taylorswift13' 
WHERE id = 4; 

SELECT * FROM celebs;
```
Hint

Double-check your statement character by character:

- Did you include the underscore in twitter_handle?
- Did you include the @ in Taylor’s twitter_handle?
Notice the single quotes around @taylorswift13. This is because text strings require quotes around them, while numbers don’t.
