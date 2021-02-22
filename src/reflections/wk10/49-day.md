# Day 49
## __2/22/2021__



## In a SQL table, what is the difference between information in a row and information in a column?
Rows hold single elements, while columns hold single properties. For example, 1 row may be  a single user, while column 1 may be the username of all users.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
This MySQL request will create a new table:
`
CREATE TABLE characters
 (
   id INT AUTO_INCREMENT,
   name VARCHAR(255) NOT NULL UNIQUE,
   description VARCHAR(255),
    name VARCHAR(255),

   PRIMARY KEY (id)
 );
`

## What is the difference between the following statements:
`DELETE FROM table_name;
DROP TABLE table_name;`

DELETE FROM will remove elements from a table. DROP TABLE will remove an entire table! This is an important distinction.
