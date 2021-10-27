# .Net and SQL relationships

**What is the difference between a primary key and a foreign key**

A primary key refers to itself the foreign key refers to the item it has a relationship with.

**What is an Alias?**

an alias is similar to a variable where you can create a shortened name to for different tables and other items in SQL

**Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:**


CREATE TABLE doctors (

  id INT NOT NULL AUTO_INCREMENT,

  -- CODE OMITTED\

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

SELECT
 p.*, 
 d.* 
 FROM patients p 
 JOIN doctors d on d.id = p.doctorId
 WHERE p.doctorId = doctorId

**Afternoon Challenge:**

https://github.com/NickSondrup/AmaZen