SELECT VERSION();
    Checks current version of MySQL.


CREATE DATABASE [Name];
USE [Name];
    Creates a database and uses it.


CREATE TABLE [Name] (
    column1 datatype,
    column2 datatype,
    ...
);
    Creates a table populated with necessary data.

    Datatypes:
        INT 
        VARCHAR(#)

    Constraints:
        NOT NULL // Column cannot have a NULL value
        UNIQUE // All values in a column are different
        PRIMARY KEY // Uniquely identifies each row in a table
        FOREIGN KEY // Prevents actions that would destroy links between tables
        CHECK // Values in a column satisfies a specific condition
        DEFAULT // Sets a default value for a column if no value is specified
        CREATE INDEX // Creates and retrieves data from database quickly


SELECT [Column/*] FROM [Table Name];
    Selects all data from a column.
    * Selects all data in the table.

INSERT INTO [Table Name] (Column1, Column2...)
VALUES ('Value1', 'Value2'...);
    Inserts new data into the table with specifications.


DESCRIBE [Table Name];
    Displays columns, their data types, nullability, default values and addition information in a table format.


TRUNCATE TABLE [Table Name];
    Deletes all inputted data in a table.


UPDATE [Table Name]
SET [Column] = value
WHERE [Column] [Condition];
    Updates data in a column with specifications.