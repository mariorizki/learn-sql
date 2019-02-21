# Using SQLite

## Table

Table:

| id  | name   | email            |
| --- | ------ | ---------------- |
| 1   | Haidar | haidar@gmail.com |
| 2   | Hanif  | hanif@gmail.com  |
| 3   | Impact | impact@gmail.com |

SQL Create Table:

```sql
CREATE TABLE users (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  name VARCHAR(50),
  email VARCHAR(50)
);
```

## Insert Data

```sql
INSERT INTO users (name, email)
VALUES
('Haidar', 'haidar@gmail.com'),
('Hanif', 'hanif@gmail.com'),
('Impact', 'impactbyte@gmail.com');
```
