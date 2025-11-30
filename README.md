# SQL Cheatsheet (PostgreSQL)
## Basic SELECT
Description: Fetch all rows from a table.
`SELECT * FROM table_name;`

## Filtering Rows

`SELECT *
FROM users
WHERE age > 25;`

## Insert Data

```
INSERT INTO users (username, email)
VALUES ('alice', 'alice@example.com');
```
