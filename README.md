#CSci 4370/6370 Database Management

###[John Miller](http://cobweb.cs.uga.edu/~jam/) and [Lakshmish Ramaswamy](http://www.cs.uga.edu/~laks/)
###Summer 2014

---

##Textbook
* [Database Systems: An Application-Oriented Approach, Complete Version, 2/E,](http://www.aw-bc.com/catalog/academic/product/0,1144,0321268458,00.html)  
Kifer, Bernstein and Lewis, 2006.  
[recommended for 4370, 6370 and 8370]
* [Database Systems: An Application-Oriented Approach, Introductory Version, 2/E,](http://www.pearsonhighered.com/educator/academic/product/0,3110,0321228383,00.html)  
Kifer, Bernstein and Lewis, 2005.  
[lower cost alternative for first course]  
(first 12 chapters almost identical, but has less material on B+Trees)

---

##Class Time (in GSRC 306)
| Day | Period 5 | Period 6 |
| --- | -------- | -------- |
| | 1:00 - 2:00 | 2:15 - 3:15 |
| Monday | yes | yes (TT) |
| Tuesday | yes | no |
| Wednesday | yes | yes (HW) |
| Thursday | yes | yes (TT) |

---

##Course Description
A comprehensive course on the use and implementation of Database Management Systems (DBMSs).

---

##Course Topics
Chapters 1 - 6, 8 - 12.

1. Overview of Databases and Transactions (Ch. 1)
2. The Big Picture (Ch. 2)
3. Relational Model (Ch. 3: 3.1-3.2)
4. Relational Algebra (Ch. 5: 5.1)
5. Physical Data Organization (Ch. 9: 9.1-9.3)
6. Indexing (Ch. 9: 9.4-9.8)
7. The Basics of Query Processing (Ch. 10: 10.1-10.5)
8. An Overview of Query Optimization (Ch. 11: 11.1-11.3)
9. SQL: Data Definition Language (DDL) (Ch. 3: 3.3)
10. SQL: Query Language (QL) (Ch. 5: 5.2-5.3)
11. Conceptual Modeling (ER and UML) (Ch. 4)
12. Relational Normalization Theory (Ch. 6: 6.1-6.8) 

---

##Grading
| Weight | Type | Info |
| ------ | ---- | ---- |
| 20% | Exam I: topics = {1, 2, 3, 4, 5, 6} | |
| 20% | Exam II: topics = {6, 7, 8, 9, 10} | |
| 25% | Final Exam | |
| 30% | Programs (groups of 4) | [Java SE 8](http://java.sun.com/javase/downloads/index.jsp), [MySQL 5.6](http://dev.mysql.com/downloads/mysql/5.6.html), [PostgreSQL 9.3](http://www.postgresql.org/download/) |
| 5% | Homework/Tool Talks | presentations |

**Exam I:** closed notes and book; bring calculator; 1 page info sheet allowed.  
Review Date: 6/25 
Exam Date: 6/26  
5 Questions:

**Exam II:** closed notes and book; bring calculator; 2 page info sheet allowed.  
Review Date:  
Exam Date: 7/21   
4 Questions:

**Final Exam:** closed notes and book; bring calculator; 4 page info sheet allowed.  
Date: 7/30  
7 Questions: 

---

##HW: Homework (individual)
Requirement: Present 1 (individual). Subject to rescheduling. 

| No. | Chapters | Questions | Due |
| --- | -------- | --------- | --- |
| 1. | Ch. 2 | (1) 2.1; (2) 2.11; (3) FMS vs. DBMS | 6/11 |
| 2. | Ch. 3 | (4) 3.3; (5) 3.4; (6) 3.5 | 6/18 |
| 3. | Ch. 5 | (7) 5.1 (8) 5.10 a-b (Relational Algebra only) | 6/25 |
| 4. | Ch. 9 | (9) 9.1 (SATA); (10) 9.1 (SAS); (11) RAID | 7/2 |
| 5. | Ch. 9 | (12) 9.7 (B+Trees); (13) 9.7 (Linear Hashing); (14) 9.7 (Extendable Hashing) | 7/9 |
| 6. | Ch. 10 | (15) 10.8; (16) 10.11 | 7/16 |
| 7. | Ch. 3, 5 | (17) 3.9; (18) 5.10 a-b (SQL only) | |
| 8. | Ch. 4 | (19) 4.3; (20) 4.7 | 7/23 |
| 9. | Ch. 6 | (21) 6.19 | 7/23 |

---

##TT: Tool Talks (group)
Requirement: Present 2 (group). Subject to rescheduling. 

| No. | Topic | Description | Talk | Due |
| --- | ----- | ----------- | ---- | --- |
| 1. | [Java 8](http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/Lambda-QuickStart/index.html) | Functional Programming in Java 8 | | 6/9 |
| 2. | [I/O Streams](http://docs.oracle.com/javase/tutorial/essential/io/streams.html) | I/O Streams in Java | | 6/12 |
| 3. | [ext4](https://ext4.wiki.kernel.org/index.php/Main_Page) | Extended File System (Linux) | | 6/16 |
| 4. | [File I/O](http://docs.oracle.com/javase/tutorial/essential/io/fileio.html) | File I/O in Java | | 6/19 |
| 5. | [MySQL 5.6](http://dev.mysql.com/doc/refman/5.6/en/index.html) | Relational Database Management System (R-DBMS) | | 6/23 |
| 6. | [PostgreSQL 9.3](http://www.postgresql.org/docs/9.3/static/index.html) | Object-Relational Database Management System DBMS (OR-DBMS) | | 6/26 |
| 7. | [JDBC](http://java.sun.com/docs/books/tutorial/jdbc) | Java Database Connectivity (JDBC) | | |
| 8. | [Struts 2](http://struts.apache.org/release/2.3.x/index.html) | Web Application Framework | | |
| 9. | JPA ([Hibernate](http://docs.jboss.org/hibernate/orm/4.2/devguide/en-US/html/), [OpenJPA](http://openjpa.apache.org/builds/2.2.1/apache-openjpa/docs/main.html)) | Java Persistence Architecture (JPA) | | |
| 10. | [jQuery/AJAX](http://jquery.com/) | Rich Internet Applications | | |
| 11. | [UML](http://www.sparxsystems.com/resources/uml2_tutorial/index.html) | Unified Modeling Language | | |
| 12. | [NoSQL](http://cobweb.cs.uga.edu/%7Ejam/home/courses/csci4370/TBA.html) | NoSQL Databases | | |

---

##Projects
[Instructions](INSTRUCTIONS.md)

**Must Extend the Code Given Below:**

| No. | Description | Starter Code (must be used) | Comment | Due |
| --- | ----------- | --------------------------- | ------- | --- |
| 1. | [Implement RA Operators: Select, Project, Union, Minus and Join](/csci4370-database_management) | [Table.java](summer14/Table.java), [KeyType.java](summer14/KeyType.java), [ArrayUtil.java](summer14/ArrayUtil.java) and [MovieDB.java](summer14/MovieDB.java) | Finish the implementation the 5 RA Operators that are partially implemented in Table.java. Store tuples in an ArrayList. Use a TreeMap for an index. | 6/20 |
| 2. | Implement the following three Index Structures: | [BpTreeMap.java](summer14/BpTreeMap.java), [LinHashMap.java](summer14/LinHashMap.java) and [ExtHashMap.java](summer14/ExtHashMap.java) | Use the indices to speed up the processing of Select and Join. | 6/27 |
| 3. |Performance Evaluation of RA Operators | [TupleGenerator.java](summer14/TupleGenerator.java), [TupleGeneratorImpl.java](summer14/TupleGeneratorImpl.java), [TestTupleGenerator.java](summer14/TestTupleGenerator.java) | Plot performance for Selects and Joins (response time in ms vs. number of tuples). Compare sequential select vs. indexed select, nested loop join vs. indexed join and TreeMap vs. all index structures. Print your Index Structure. Present performance results. Gold (+6), silver (+4) and bronze (+2) medals for best performers. | 7/3 |
| 4. | Performance Tuning of SQL Queries | See queries below | Analyze query plans generated by the DBMS. Tune queries by using hints, adding indexes and rewriting queries. Explain how query plans change after tuning. Turn in before and after .sql files and query plans for six queries (given in English, see below). Do this for both the MySQL and PostgreSQL DBMSs: [MySQL](http://dev.mysql.com/doc/refman/5.6/en/optimization.html) and [PostgreSQL](http://www.postgresql.org/docs/9.3/interactive/internals.html). Present tuning experience and performance results including plots in class. | 7/11 |
| 5. | Term Project: Database Application with Web Access | | A two-page proposal giving a detailed description of the application you propose to develop must be submitted on 7/11. Project includes database design (UML, Normalization), population and Web-based application development. The DBMS must be either MySQL or PostgreSQL. The Web development framework must be [Struts 2](http://struts.apache.org/development/2.x/index.html), or [jQuery](http://jquery.com/). Access to the database must be via either JDBC or JPA. The term project including a demo will be presented during the last week of class. Worth twice the points of regular programming projects. | 7/28, 7/29 |

**Plots with [error bars](http://en.wikipedia.org/wiki/Standard_error_%28statistics%29#Assumptions_and_usage) of Performance Results for Project 3:**

1. **Select - Point Query:** σ id = v (Student)
	* Table Scan - ArrayList
	* Indexed Select - ArrayList, TreeMap
	* Indexed Select - ArrayList, BpTree
	* Indexed Select - ArrayList, LinHash
	* Indexed Select - ArrayList, ExtHash 
2. **Select - Range Query:** σ v1 <= id & id <= v2 (Student)
	* Table Scan - ArrayList
	* Indexed Select - ArrayList, BpTree
	* Indexed Select - ArrayList, LinHash 
3. **Join:** Student join id = studId Transcript
	* Nested Loop Join - ArrayList
	* Indexed Join - ArrayList, TreeMap
	* Indexed Join - ArrayList, BpTree
	* Indexed Join - ArrayList, LinHash
	* Indexed Join - ArrayList, ExtHash 

**Queries for Project 4:**

1. List the name of the student with id equal to v1 (id).
2. List the names of students with id in the range of v2 (id) to v3 (inclusive).
3. List the names of students who have taken course v4 (crsCode).
4. List the names of students who have taken a course taught by professor v5 (name).
5. List the names of students who have taken a course from department v6 (deptId), but not v7.
6. List the names of students who have taken all courses offered by department v8 (deptId). 

----

##Policies

* Late Points - 10 points off per day late.
* Make-Up Tests - written pre-approval or medical documentation required (no retakes).
* [A Culture of Honesty](http://www.uga.edu/honesty) -- [Examples](http://www.uga.edu/honesty/ahpd/prohibited_conduct.html).
* [Copyright Issues](http://www.ctl.uga.edu/teach_asst/copyright.htm) -- [Regents Guide to Understanding Copyright](http://www.usg.edu/legal/copyright).
