# Data Modeling

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

## nosql vs sql

What type of database is the best fit for the complex query intensive environment?

A relational database is typically the best fit for a complex, query-intensive environment.

What type of database is the best fit for hierarchical data storage?

A document-oriented database, such as MongoDB, is often the best fit for hierarchical data storage.

Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

SQL databases are generally more structured and support complex queries, but can be less scalable than NoSQL databases, which are more flexible and can handle a larger volume of unstructured data but may not support as many complex queries.

### sql modeling techniques

Among data tables, what is a one-to-many relationship and how do we “relate” them?

A one-to-many relationship between data tables means that one row in the first table can be related to many rows in the second table. We "relate" these tables by using a foreign key in the second table that refers to the primary key in the first table.

Prior to designing your relational database, it might be useful to `___ a ___` of the database tables and their relationships.

Prior to designing your relational database, it might be useful to create a diagram of the database tables and their relationships.

Explain the difference between a primary and foreign key.

A primary key is a field in a table that is used to uniquely identify each row in the table, while a foreign key is a field in a table that refers to the primary key in another table

### sql vs nosql

How do we treat keywords and parameters differently in SQL syntax?

In SQL syntax, keywords are typically written in all uppercase and are used to specify the commands and clauses being used in a query, while parameters are placeholders for values that will be supplied when the query is executed

Define normalization within the context of schemas and data.

Normalization in the context of schemas and data refers to the process of organizing a database in such a way as to minimize redundancy and dependency.

Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

A one-to-one relationship means that each row in one table is related to exactly one row in another table, a one-to-many relationship means that each row in the first table can be related to many rows in the second table, and a many-to-many relationship means that each row in one table can be related to many rows in the other table.