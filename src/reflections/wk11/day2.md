# Day 2 - MYSQL RELATIONSHIPS (MANY-TO-MANY):

## Daily Challenge - Morning:

_[Products API]()_
<br> <br>

## Daily Project:

_[Amazen](https://github.com/IDMiller2020/spring21-amazen)_
<br> <br>

## Daily Challenge - Afternoon:

_[Contracted](https://github.com/IDMiller2020/week11-day2-contracted)_
<br> <br>

## Daily Journal:

## Read [Read Dotnet WebAPI's > Relationships](https://codeworksacademy.com/fs-student-guide/resources/wk11/02-MySQL-Relationships/#primary-keys) and answer the following questions:

1. What is the difference between a primary key and a foreign key? <br>
   _A Primary Key is the unique identifier of the row. A Foreign key is a key that comes from a different row to establish a relationship between the two rows._ <br>
   <br>
2. What is an Alias? <br>
   _Aliases are used to differentiate data that is identified by the same key in two different tables._ <br>
   <br>
3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections: <br>
   CREATE TABLE doctors (
   id INT NOT NULL AUTO_INCREMENT,
   -- CODE OMITTED
   PRIMARY KEY (id)
   )

CREATE TABLE patients (
id INT NOT NULL AUTO_INCREMENT,
-- CODE OMITTED
PRIMARY KEY (id)
)

CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
doctorId INT NOT NULL,
patientId INT NOT NULL,

FOREIGN KEY (doctorId)
REFERENCES doctors(id),
FOREIGN KEY (patientId)
REFERENCES patients(id),
)
\_\_ <br>
