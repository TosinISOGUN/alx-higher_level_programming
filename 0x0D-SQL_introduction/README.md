# SQL - Introduction

<p align="center">
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/272/rtcwz.jpg" width="" height="" />
</p>

## Synopsis (SQL Overview)
`SQL` is *Structured Query Language*, which is a computer language for storing, manipulating and retrieving data stored in a relational database.

> SQL is a language to operate databases; it includes database creation, deletion, fetching rows, modifying rows, etc. `SQL` is an **ANSI** (American National Standards Institute) standard language, but there are many different versions of the SQL language.

This is an ALX Holberton School project and we are tasked with familiarizing ourselves with storing, manipulating and retrieving of data using SQL.

## Table of Contents
| Files | Description |
| --- | --- |
| 0-list_databases.sql | a script that lists all databases of your MySQL server. |
| 1-create_database_if_missing.sql | a script that creates the database `hbtn_0c_0` in your MySQL server; If the database `hbtn_0c_0` already exists, the script should not fail. |
| 2-remove_database.sql | a script that deletes the database `hbtn_0c_0` in your MySQL server; If the database `hbtn_0c_0` doesn’t exist, the script should not fail. |
| 3-list_tables.sql | a script that lists all the tables of a database in your MySQL server; The database name will be passed as argument of `mysql` command (in the following example: `mysql` is the name of the database). |
| 4-first_table.sql | a script that creates a table called `first_table` in the current database in your MySQL server; The database name will be passed as an argument of the `mysql` command. |
| 5-full_table.sql | a script that prints the full description of the table `first_table` from the database `hbtn_0c_0` in your MySQL server; The database name will be passed as an argument of the mysql command and the use of the `DESCRIBE` or `EXPLAIN` statements are not allowed.
| 6-list_values.sql | a script that lists all rows of the table `first_table` from the database `hbtn_0c_0` in your MySQL server; (1) All fields should be printed (2) The database name will be passed as an argument of the `mysql` command.
| 7-insert_value.sql | a script that inserts a new row in the table `first_table` (database `hbtn_0c_0`) in your MySQL server; (1) New row `id` = `89`, `name` = `Best School` (2) The database name will be passed as an argument of the mysql command.
| 8-count_89.sql | a script that displays the number of records with `id = 89` in the table `first_table` of the database `hbtn_0c_0` in your MySQL server. |
| 9-full_creation.sql | a script that creates a table `second_table` in the database `hbtn_0c_0` in your MySQL server and add multiples rows. |
| 10-top_score.sql | a script that lists all records of the table second_table of the database hbtn_0c_0 in your MySQL server. |
| 11-best_score.sql | a script that lists all records with a `score >= 10` in the table `second_table` of the database `hbtn_0c_0` in your MySQL server. |
| 12-no_cheating.sql | a script that updates the score of Bob to `10` in the table `second_table`. |
| 13-change_class.sql | a script that removes all records with a `score <= 5` in the table `second_table` of the database `hbtn_0c_0` in your MySQL server. |
| 14-average.sql | a script that computes the score average of all records in the table `second_table` of the database `hbtn_0c_0` in your MySQL server. |
| 15-groups.sql | a script that lists the number of records with the same score in the table `second_table` of the database `hbtn_0c_0` in your MySQL server. |
| 16-no_link.sql | a script that lists all records of the table `second_table` of the database `hbtn_0c_0` in your MySQL server. |
| 100-move_to_utf8.sql | a script that converts `hbtn_0c_0` database to UTF8 (`utf8mb4`, collate `utf8mb4_unicode_ci`) in your MySQL server. |
| 101-avg_temperatures.sql | a script that displays the average temperature (Fahrenheit) by city ordered by temperature (descending). |
| 102-top_city.sql | a script that displays the top 3 of cities temperature during July and August ordered by temperature (descending) |
| 103-max_state.sql | a script that displays the max temperature of each state (ordered by State name). |


## Requirements and Environment
<img src="https://alx-apply.hbtn.io/brand_alx/share_image_2019.jpg" width="300" height="100" />

- Allowed editors: `vi`, `vim`, `emacs`.
- All files will be executed on `Ubuntu 20.04 LTS` using **MySQL 8.0** (version 8.0.25)
- All files should end with a new line.
- All SQL queries should have a comment just before (i.e. syntax above)
- All files should start by a comment describing the task.
- A `README.md` file, at the root of the folder of the project, is mandatory.
- The length of files will be tested using `wc`.
 

## Authors & Credits
- [Oluwatomisin Isogun](https://@github.com/TosinISOGUN)
> Other collaborators (if there are any), will be acknowledged in the project repository.
