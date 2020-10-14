# Introduction
This project is part of my **Intro to Database Management** graduate class. The goal of the project is to create a working database system. All models are drafted using Orcale Model Developer.

The business rules for this project are as follows:

*School of Natural Sciences and Allied Health at Cabrini University contains many departments. Each
department may offer any number of courses. A course must belong to exactly one department. A department
may have many instructors, but an instructor can work only in one department. For each department, there is a
head, and an instructor can be head of only one department. Each instructor can teach any number of courses, and
a course can be taken by only one instructor. Each course can generate a class. Not all classes are offered every
semester. A student can enroll for any number of courses and each course can have any number of students. Each
department can have any number of students. A student can be a part of only one department. Each department
can offer any number of majors. Many students can declare any combination of degree type and major. Each
class is held in one room. Each room can hold many classes. Each room belongs to one building. An instructor has
their office in one room. A department is in one room.*

# Description of Files

### Conceptual Model
This is the first step in the database design process. Here, we define the relationships between each table.

### Logical Model
This is the second step in the database design process. Here, we define the attribute names.

### Physical Model
This is the third step in the database design process. Here, we define primary/foreign keys as well as the types of each attribute.

### Construction of Models
This file contains a report describing how each model was constructed and how it satisfies the business rules.

### Normalization of Database Tables
This file contains a report describing how to normalize tables in a database. The goal was to transform each table to third normal form (3NF).

### Fake Data for Database
This is a python notebook that creates fake data for this database.

### DDL and DML and Queries
This file contains a report describing the:
  + DDL (Data Definition Language) that was used to create the tables and their primary/foreign keys. 
  + DML (Data Manipulation Language) that was used to populate the tables with data.
  + Queries that demonstrate that the database is designed correctly.

### Star Schema
This file contains a report describing how a star schema was built for this database. The star schema is to be used in a data warehouse.
