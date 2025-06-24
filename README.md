----1 What is PostgreSQL?
Ans: PostgreSQL is a powerful, open-source object-relational database system. It supports advanced data types and performance optimization features.
Using it, you can store, manage, and analyze data with high reliability.
Open-source – completely free and open to everyone. Relational database – data is stored in the form of tables.Security – Supports user permissions and encryption. Advanced Query – Can run complex SQL queries. Extension Support – Can manage geographic data using extensions like PostGIS.

----2 What is the purpose of a database schema in PostgreSQL?
Ans: A database schema in PostgreSQL serves as a way to organize, group, and manage database objects like tables, views, functions, and indexes within a database.Think of a schema like a folder inside a database.
Just like a folder helps organize files on your computer, a schema helps organize tables and other items inside your PostgreSQL database.
A database can have two schemas:
admin.users → Admin users information
client.users → Client users information
The two tables are named users, but there is no problem because they are in different schemas.

----3 Explain the Primary Key and Foreign Key concepts in PostgreSQL.
ans:
Primary key: A Primary Key is a column (or group of columns) in a table that uniquely identifies each row in that table.
It must be unique and cannot be NULL.
Foreign Key: A Foreign Key is a column in one table that links to the Primary Key of another table.
It creates a relationship between two tables.

----4 What is the difference between the VARCHAR and CHAR data types?
Ans:
VARCHAR:Variable-length character.Can store up to n characters.Uses only required space.Better for variable-length data.Does not pad spaces.
CHAR:Fixed-length character.Always stores exactly n characters.Fills with extra spaces to match length.Better for fixed-length fields (like codes).Pads with spaces if shorter than 


----5 What is the significance of the JOIN operation, and how does it work in PostgreSQL?
Ans:The JOIN operation is used to combine data from two or more tables based on a related column between them—typically a foreign key. It's essential for working with normalized databases where data is split across multiple tables to avoid duplication and improve data integrity.
1 INNER JOIN	Returns only matching rows in both tables.
2 LEFT JOIN	Returns all rows from the left table, even if there’s no match in the right.
3 RIGHT JOIN	Returns all rows from the right table, even if there’s no match in the left.
4 FULL JOIN	Returns all rows when there is a match in one of the tables.




