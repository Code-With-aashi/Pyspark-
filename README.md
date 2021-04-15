The Dataset used in first project can be downloaded from "https://drive.google.com/file/d/1lZNjlivBPOWe9ln2Pik5bBsTj-Vrf2e6/view?usp=sharing" or you can directly downloaded from kaggle "https://www.kaggle.com/fireballbyedimyrnmom/us-counties-covid-19-dataset".
# For first project (Analysis of Covid 19 Dataset of US)
# Pyspark-
Apache Spark is written in Scala programming language. PySpark has been released in order to support the collaboration of Apache Spark and Python, it actually is a Python API for Spark. In addition, PySpark, helps you interface with Resilient Distributed Datasets (RDDs) in Apache Spark and Python programming language. This has been achieved by taking advantage of the Py4j library. PySpark LogoPy4J is a popular library which is integrated within PySpark and allows python to dynamically interface with JVM objects. PySpark features quite a few libraries for writing efficient programs.
# Following topics have been covered here:
* Setting up the environment
* Loading the dataset into Pyspark
* Applying Filters
* Group by and Aggregation
* Joins (left, right, inner, full)
* Partition By & Window Function
* Automating the code
# Different Types of SQL JOINs
Here are the different types of the JOINs in SQL:
![sql-joins](https://user-images.githubusercontent.com/41945372/113957252-7f87d480-983c-11eb-88c7-5a8ce259ac96.png)
* (INNER) JOIN: Returns records that have matching values in both tables
* LEFT (OUTER) JOIN: Returns all records from the left table, and the matched records from the right table
* RIGHT (OUTER) JOIN: Returns all records from the right table, and the matched records from the left table
* FULL (OUTER) JOIN: Returns all records when there is a match in either left or right table

# The Dataset used in second project can be downloaded from "https://www.kaggle.com/usdot/flight-delays"


# For Second Project (Analysis of flights,airport and airlines)
* Setting up the environment
* Loading the dataset into Pyspark
* Applying Filters
* Merging two dataset using a primary key
* Group by and Aggregation
# Types of SQL keys are:
 * Super Key =
Super key is a set of one or more than one keys that can be used to identify a record uniquely in a table. Example: Primary key, Unique key, Alternate key are a subset of Super Keys.

* Candidate Key =
A Candidate Key is a set of one or more fields/columns that can identify a record uniquely in a table. There can be multiple Candidate Keys in one table. Each Candidate Key can work as Primary Key.

* Primary Key =
Primary key is a set of one or more fields/columns of a table that uniquely identify a record in a database table. It can not accept null, duplicate values. Only one Candidate Key can be Primary Key.

* Alternate key =
An Alternate key is a key that can be work as a primary key. Basically, it is a candidate key that currently is not a primary key.

* Composite/Compound Key =
Composite Key is a combination of more than one fields/columns of a table. It can be a Candidate key, Primary key.

* Unique Key =
A unique key is a set of one or more fields/columns of a table that uniquely identify a record in a database table. It is like Primary key but it can accept only one null value and it can not have duplicate values. 

* Foreign Key =
Foreign Key is a field in a database table that is Primary key in another table. It can accept multiple null, duplicate values. 
