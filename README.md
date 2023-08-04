# Simple DBMS

Simple DBMS is a basic command-line based Database Management System (DBMS) written in C++. It allows users to create databases, define tables, insert data, query data, delete data and update data using SQL-like commands.

## Introduction

This project is a simple implementation of a DBMS using C++. It provides basic functionalities to create, manage, and query databases. The primary goal of this project is to demonstrate the fundamental concepts of a DBMS and provide a starting point for building more complex systems. And datas are saved in separate files.

## Features
- Create and manage databases
- Define and manage tables within databases
- Insert data into tables
- Query data from tables using SELECT statements
- Update data in tables using UPDATE statements
- Delete data from tables using DELETE statemnets

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NalbandyanE/MyDBMS.git
   ```
2. Build the project:
   ```bash
   cd MyDBMS
   ```
   ```bash
   g++ src/field.cpp src/row.cpp src/table.cpp src/dbms.cpp src/command.cpp src/commandValidator.cpp src/commandExecutor.cpp main.cpp
   ```
   ```bash
   ./a.out
   ```

### Usage

Once the DBMS starts, you can enter SQL-like commands to interact with the database.

## Commands
- `CREATE DATABASE <db_name>;` - Creates a new database with the given name.
- `CREATE TABLE <table_name>;` - Creates a new table with the given name.
- `INSERT INTO <table_name> (<column1>, <column2>, ...) VALUES (<value1>, <value2>, ...);` - Inserts a new row of data into the table.
- `SELECT <column1>, <column2>, ... FROM <table_name>;` - Queries data from the table and retrieves the specified columns.
- `UPDATE <table_name> SET <column1>=<value1>, <column2>=<value2>, ... WHERE <condition>;` - Updates data in the table based on the specified condition.
- `DELETE FROM <table_name> WHERE <condition>;` - Delete data from table based on the specified condition.

## Contributing

Contributions are welcome! If you find any bugs or have ideas for improvements, please open an issue or submit a pull request.
