# How to create, insert data and filter tables in SQLite!

### - File creation
We can use the argument ".open", it allow us open previous files and create news. 
>
.open FileName

### - Table creation
We will use the argument "Create table title-name" we must remember that SQL is not case sensitive.
>
Create table staff

However from here on we must round off with parenthesis the arguments that we will use we will finish whit semicolon.
>
Create table staff();

#### - how to define the data we will use
Normally we use data such as
* Name
* Last_Name
* ID
* Position
* Number
* Mail

These must be accompanied by the aproximate amount of data, we will use "varchar()" for text and "numeric()" for numbers.
>
Name varchar(15),
Last_Name