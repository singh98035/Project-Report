# Project-Report
  Firstly our Goal of this project find the attainment of each course's outcomes and then the attainment of final course, which we calculate the attainment by the individual student
  Achieve the goal of project we all mates work on some modules.
 1. Installation  of  moodle.
 
      Firstly we study about moodle installation process on windows from internet follow the documentation of moodle [https://docs.moodle.org/38/en/Windows_installation](https://docs.moodle.org/38/en/Windows_installation)   download the moodle package from [https://download.moodle.org/releases/latest/](https://download.moodle.org/releases/latest/) then install the localhost server like xampp from that link [https://www.apachefriends.org/download.html](https://www.apachefriends.org/download.html).
      After that we all face  many problems and error like Execution time 60sec it takes too many times and waste 2 or 3 days.
After facing the problems than  we all exploring the internet as told by our mentor the we find the bitnaami and find the exe file of moodle that easy to install in our machine download it from [https://bitnami.com/stack/moodle/installer](https://bitnami.com/stack/moodle/installer).
After that our mentor gave the command to study the database of moodle
Yesterday
 we all study the database schema of moodle from documentation[https://docs.moodle.org/dev/Database_schema_introduction](https://docs.moodle.org/dev/Database_schema_introduction)
 After that we study the moodle database contain 200 tables.The big problem is this we don't have to understand it all at once.the good thing is that only that tables to understand useful for project and forgot all. after that i study the constraints two table like "assign" is used for assignment module the "assign" table is join with others tables. 2nd table is "course" .After our mentor provide the some Documents to understand the course outcomes, program outcomes and attainment. 
 
 at least one query occurs in mind you can say question.
 
we all don't study the all tables. the query is that what table is important for project?how many tables we will study?

**March-30-2020**
***Yesterday***, In my Mind a query occur regarding Database Table ,Today I clear the  query and work on that and Understanding those
table that useful for project.
 As said by our mentor only **mdl_assign and mdl_course** table is used for understand the databse like *what table store the course related data* and *What table is used for storing the data relate with assignment,quiz and another activity*.
 for that purpose i can create the users and switch the roles to the users role like teacher,Student,Manager etc.In moodle Dashboard
 the user have **teacher role** that
 
   1.create the course
   2.After that add the participants like add the user in the course which role switch to *Student*-- 
After that i see the data entries stored in tables like course information stored in database table
As teacher assign the assignments to user(students)
At the view of student submit the assignment and i see the databse **mdl_assign** table that store the submissions and teacher give the grade shown student view also in the database table like **mdl_assgin_grades**.
In other words, I can say that 1 check the _database activity_ fill entries in the frontend part and see the backend for which table store assignment and course related data stored.

**March-31-2020**   *No work today*


  
 

      
  
