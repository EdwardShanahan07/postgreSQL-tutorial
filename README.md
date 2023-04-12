# PostgreSQL Tutorial

## Commands 
Create new database 
```shell
postgres=# CREATE DATABASE DATABASE_NAME;
```

Connect to database
```shell
postgres=# \c DATABASE_NAME;
```

Quit Postgres CLI
```shell
postgres=# \q
```

Shorthand to connect to database
```shell
$ psql -d DATABADE_NAME
```

Display tables
```shell
postgres=# \dt
```

Retrieve all data from a table
```shell
postgres=# SELECT * FROM "TABLE_NAME";
```

Get data from a column
```shell
postgres=# SELECT "name" FROM "COLUMN_NAME";
```

Get specific data value from column
```shell
postgres=# SELECT * FROM "COLUMN_NAME" WHERE = 'QUERY';
```