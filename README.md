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

**March-31-2020**   *No work today*--
### April-01-2020
Today, Our Respected Mentor Gave the task for our practice like  install game plugin in moodle and check the backend how the tables are created in the database. 
Have No knowledge about plugin installation than moodle's documention guide installation process.
Firstly, go to ***site administration***, Open the plugin and Install new Plugin. After the Window Shows the two method to install plugin .
>1. Download the plugin from moodle's plugin directory
>2.Choose the zip folder.
    I am choose the First option. now its directly open moodle official website:-[https://download.moodle.org/](https://download.moodle.org/). After select the plugin than seach the plugin you want to install.
    After, press on install button the installation process starts in few seconds. 
  Complete the process and press upgrade moodle than dashboard is open.the game plugin provide more games like sudoku,snakes and ladder.
  follow the same steps for add the game *Activity* like quiz,assignment.
  fill the all required fields than add.
  After adding the game activity. check the backend manully, it automatically creates required table for game plugin.
  
 ## April-o2-2020.
 Today we tried to create a formula to calculate the attainment, with help of pdf sent by our mentor **Dr.Amit Kamra Sir**. which I found the table which has some data write the course outcomes. But there I found a problem ablout data i.e what that data contains that was not understandable. So after that I ping to our mentor. And also we are today assigned with the work to find the code for assignment in which we can make changes and try to add a new column at frontend. But couldn't find the code and instead that we find the code for certificate form https://docs.moodle.org/dev/Activity_modules. We try to find the code for assignment.
 
