Query Impala in R
=================

## Dependencies
- R package `RJDBC` -> allows R to connect to any DBMS that has a JDBC driver
- Impala JDBC Drivers

## Usage

- Fill in the variable `impalaConnectionUrl`, the url used to open a connection on Impala
- Replace the value `impala_jdbc_folder_path` with the name of the impala drivers folder in the function `JDBC()`
- Replace the value of the database parameter `dbname` in the function `dbConnect()` with the target database name
