# Celestial Bodies Database for freeCodeCamp's Relational Database certification

## This is the first required project for the Relational Database certification.

##The tasks were: 

- Create a database named <universe>
- The database will have the tables: <galaxy>, <star>, <planet>, <moon>
- Each table must have a primary key
- Each primary key should automatically increment
- Each table should have a <name> column
- At least two columns that are not a primary or foreign key must have a INT data type
- At least one column needs the NUMERIC data type
- At least one column needs the TEXT data type
- At least two columns needs the BOOLEAN data type
- Each "star" should have a foreign key that references one of the rows in <galaxy>
- Each "planet" should have a foreign key that references one of the rows in <star>
- Each "moon" should have a foreign key that references one of the rows in <planet>
- The database should have at least five tables
- Each table should have at least three rows
- The <galaxy> and <star> tables should each have at least six rows
- The <planet> table should have at least 12 rows
- The <moon> table should have at least 20 rows
- Each table should have at least three columns
- The <galaxy>, <star>, <planet>, and <moon> tables should each have at least five columns
- At least two columns per table should not accept NULL values
- At least one column from each table should be required to be UNIQUE
- All columns named <name> should be of type VARCHAR
- Each primary key column should follow the naming convention <table_name_id>. For example, the <moon> table should have a primary key column named <moon_id>
