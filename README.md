# Information-Systems-and-Databases

 

INFORMATION SYSTEMS AND DATABASES  

Week 1: Lec 1  

Data Base Approach  

Data Definition Language (DDL) - specification of data types, structures, constraints 

Data Manipulation Language (DML) - enquiry facility (query) for retrieving data 

 		Data CONTROL Language (DCL) - grants users' access and privileges to the database						-controlled access to the database including 

- A security system  

- An integrity system  

- A concurrency system  

- A recovery System 

- A user accessible catalog  

- and a view mechanism – restricts users to the sub-set 						  data they need  

 

Tree-Level Database Architecture & Data Independence 

External Level – Users’ view – the part of the database that is relevant to a particular user 

Conceptual Level – Community – view  

External Level – physical view of the database – describes how the data is stored in the database 

 

 

 

 

 

Data Independence  

LOGICAL Data Independence – changes to conceptual schema No changes to external schema 

PHYSICAL Data Independence – changes in the internal schema NO changes conceptual 

 

 

The Relational Model  

 

![image](https://user-images.githubusercontent.com/72341578/154869330-969a5011-0996-461e-b428-aaa844bb714b.png)


Structure: Relations (table) 

Relation – a table 

Attribute – the name of the column  

Tuple – the row  

Domain – the set of allowed values for an attribute 

Degree – the number of attributes it contains  

Cardinality – the number of tuples it contains 

 

Behavior: Integrity (how a relations (tables) behave- the rules they must follow  

2 Basic Rules:  

1. Entity Integrity : PRIMARY KEY 

- every row must be unique – Primary Key for each table 

-Candidate Key: nr of keys to guarantee uniqueness 	 

- Composite Key: 

- One of the Candidate keys become – PK, the rest are called “alternate keys” 

- ALL parts of the PK must have a value (no null attributes) 

2. Referential Integrity: FOREING KEYS 

- FK is an attribute in95 relation which is also a primary key in another  

 

Manipulation: Relational algebra  

4 traditional ‘set theory’ operations  

- UNION | INTERESECT | DIFFERENCE – they work only on two union compatible relations (must have the same number of columns)  

	 

 

 

 

4 additional special relational ops  

PROJECT sg relation, vertical subset (COLOANE), eliminates duplicate tuples 

 

SELECT (RESTRICT) - sg relation, horizontal subset (ROWS),  

 

JOIN 

DIVIDE 

 

 

 

 

 

 

 
