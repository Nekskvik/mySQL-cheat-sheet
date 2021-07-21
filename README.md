# MySQL Cheat Sheet
--------------------

## Basic comands

### Display Databases
```
SHOW database;
```

### Create Database
```
CREATE database;
```

### Delete Database
```
DROP database;
```

### Create Database Table
```
CREATE TABLE nameOfTable (pass fields that are needed);
```

### Delete Database Table
```
DROP TABLE nameOfTable;
```

### Check the appearance of a table
```
DESC nameOfTable;
```

### Insert in a table
```
INSERT INTO nameOfTable (what to insert);
```

### Insert into spacific fields
```
INSERT INTO nameOfTable (field1, field2) VALUES (value1, value2);
```

### Select all from table
```
SELECT * FROM nameOfTable;
```

### Select spacific fields from table
```
SELECT field1, field2 FROM nameOfTable;
```
```
SELECT field1, field2 FROM nameOfTable WHERE id = 7;
```
```
SELECT field FROM nameOfTable WHERE field LIKE '%ok'
% - means that it's important that string contains some signs before or combination
_ - means that only one sign has to go before our select signs
"" - empty(space) means that we passed an end point of a string
```

### Range selection
```
SELECT field FROM list WHERE some-field BETWEEN something AND something
```
reversed would be ("not" comes into play):
```
SELECT field FROM list WHERE NOT some-field BETWEEN something AND something
```
-------
#### DDL - create objects
#### DML - manage objects
#### DCL - confirm rights to run a particular comand
