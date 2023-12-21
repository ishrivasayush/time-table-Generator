<div align="center"><h1><b>AUTOMATED TIME-TABLE GENERATOR</b><br> (Using Java Swings)</h1>

![Screenshot (761)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/5675b74f-0e15-47c7-ba35-2759f272e319)


## Introduction
Time Table Scheduling is an NP-hard problem and hence polynomial time verifiable using java. It a typical scheduling problem that appears to be a tedious job in every academic institute once or twice a year. In earlier days, time table scheduling was done manually with a single person or some group involved in task of scheduling it manually, which takes a lot of effort and time. Planning timetables is one of the most complex and error-prone applications.
Timetabling is the task of creating a timetable while satisfying some constraints. There are basically two types of constraints, soft constraints and hard constraints. Soft constraints are those if we violate them in scheduling, the output is still valid, but hard constraints are those which if we violate them; the timetable is no longer valid. The search space of a timetabling problem is too vast, many solutions exist in the search space and few of them are not feasible. Feasible solutions here mean those which do not violate hard constraints and as well try to satisfy soft constraints. We need to choose the most appropriate one from feasible solutions. Most appropriate ones here mean those which do not violate soft constraints to a greater extent. In this project hard-constraints have been taken care of strictly and it has been ensured that soft-constraints are as well followed as much as possible.

**Soft-constraints (flexible):**

  •	More or less equal load is given to all faculties

  •	Required time (hours per week) is given to every Batch

**Hard-constraints (rigid):**

  •	There should not be any single instance of a faculty taking two classes simultaneously

  •	A class group must not have more than one lectures at the same time

## Getting Started

Instructions to use this project :

This project is configured in eclipse and is a simple implementation

  * Clone this repository.

  * Import the project in NetBeans ( you can even copy the package into a new project if you use a different IDE / If import of Eclipse project doesnt work well with that IDE )

  * Import users.sql file in your database

  * Set your database credendtials in line no 10-11 in UserDao.java 
```java
  Class.forName("com.mysql.jdbc.Driver");
  con = DriverManager.getConnection("jdbc:mysql://localhost:3306/test", "", "");
```	    

  * Put the input.txt file anywhere in the drive and give its location in inputdata.java at line no 33
```java
  File file = new File("c:\\test\\input.txt");
```

Cheers !

PS : Contributing back to this project will be appreciated.

## Prerequisites

  * Java 8
  
  * Netbeans(compatible with Enterprise Edition)
  
  * Local Server
  
  * MySql Database

## Running the tests

Click 'Get Started with us today' on homepage

Login (username: ayushstwt password: ayush@123)

Click on 'Test with custom input'

## Deployment

You need to load the required jar files to make this project run

## Built With

  * CORE JAVA
  * Swings
  * AWT
  * Netbeans
  * MySql

## Screenshots

![Screenshot (762)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/243ca391-fc03-49b7-adc2-e71b5d17daf9)

![Screenshot (763)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/3fe05ba7-e1b4-4368-9a2c-c63d1dd50272)

![Screenshot (764)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/a91a32ef-0b2d-4ae5-bafc-4acca2b93d68)

![Screenshot (765)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/8860b8d2-738b-48ce-a7a2-6962623afaa9)

![Screenshot (766)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/afca8039-6a0a-4d22-8b1f-3fa25919d21d)

![Screenshot (767)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/561edeab-9b33-48e9-9a3d-9ad2ab40be5f)

![Screenshot (768)](https://github.com/ishrivasayush/time-table-Generator/assets/103355440/f6049e26-ab5c-41e2-8292-233afa013cf9)







  
  
## Conclusion and Further Work

### Conclusion
The process of Time Table generation has been fully automated with this software. This web app can now cater to multiple colleges, universities and schools which can rely on it for their Time Table scheduling which earlier had to be done by hand.

### Evaluation
Using Genetics Algorithm, a number of trade-off solutions, in terms of multiple objectives of the problem, could be obtained very easily. Moreover, each of the obtained solutions has been found much better than a manually prepared solution which is in use.

### Further Work
•	Though this web-app serves as a basic time table generator, there is a lot more which could be done to make this project even better in terms of consideration of soft constraints like professor giving preference to particular class.

•	The up-gradations I look up to currently will be Classroom size considerations, lab facility consideration and multiple subject selection for faculty. I will try to bring the following up-gradations very soon.

•	More features such as schedule print for individual faculty etc. would also be involved to make this more useful as a final product.


## Author 

**Ayush Shrivastava**


<i>PS: Project Report(in pdf) is available in root folder as AutomatedTimeTableGenerator.pdf</i>
