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
  
 ### April-02-2020.
 Today we tried to create a formula to calculate the attainment, with help of pdf sent by our mentor **Dr.Amit Kamra Sir**. which I found the table which has some data write the course outcomes. But there I found a problem ablout data i.e what that data contains that was not understandable. So after that I ping to our mentor. And also we are today assigned with the work to find the code for assignment in which we can make changes and try to add a new column at frontend. But couldn't find the code and instead that we find the code for certificate form https://docs.moodle.org/dev/Activity_modules. We try to find the code for assignment.
 
 ### April-03-2020.
  Our mentor gave the work to create a flowchart or DFD what we are doing in the project. *Today* we together make a flowchart.
 **FlowChart**
![flowchart image](https://github.com/singh98035/project-SDLC/blob/master/Untitled%20Diagram.jpg).

> **1.**
   Start the process.<br />
> **2.** 
  Take input as 'course outcome' from the teacher in the textbox.<br />
> **3.**
  Store in the database.<br />
> **4.**
  Fetching the grades for particular CO.<br />
> **5.**
  Calculating course outcome attainment scored by student. <br />
  >**6.** 
    Storing attainment in the database. <br />
  >**7.**
    Display attainment at moodle or another page. <br />
  >**8.**
    End <br />
    After that I tried to understand the source code of Assignment Plugin. I understand the liitle bit code. i try to understand more code.<br />
### April-16-2020.

***Firstly*** we define the ***Competence*** <br />
competency is a bundle of **Knowledge**, **skills** , **attitude** and habits that allow an  employee to perform effectively. <br />
**Competency Framework**<br />
It is a pre-defined competencies an employee just acquire programmatically over time.A ***Competency Framework*** is meant to ensure Alignment between ***What The employee should be able to do*** and ***What The organization should be doing***.<br />
It is necessary for. <br />
1.More Precision-targeted training. <br />
2.Brighter Promotional prospects
3.Clearer carrer - Pathing
4.Deeper Sense of contribution
For Example:-I suppose am a HR.i've learned from my co-worker in the other department that they have issue with their **Training**,**Promotional Prospects**,**Career Paths** and **Sense** of countribution.This could mean that there is an issue of alignment within the organization. could this mean that those employees aren't fully fit for purpose.
<br />
Competency framework can help resolve this issue of alignment.it is make the employee fit-for purpose.
**There are few steps for developing a competency framework**<br />
1.Job Analysis and Task Analysis. <br />
2.Framework Design. <br />
3.Instructional Material Development. <br />
4.Implementation. <br />
5.Outcome evalution. <br />
>If we succeed in developing a ***Competencey Framework*** together then, we can address the issue of alignment.
<br />
in moodle we see the competence in the site administration.
in which we can check add the famework and select the framework for activity like assignment etc.

### April-16-2020.

Today, we studied in brief about competence and our provide some link related to moodle competence framework. <br />
***Firstly we have the link about competence***.[ https://docs.moodle.org/38/en/Competencies]( https://docs.moodle.org/38/en/Competencies). <br />
Which we study about competence, Competencies describe the level of understanding or proficiency of a learner in certain subject-related skills. Competency-based education (CBE), CBE for admins, teacher and student.
>In which we study about **How to setup it?** how we can enable this ?. after we study about outcome on this link [https://docs.moodle.org/38/en/Outcomes](https://docs.moodle.org/38/en/Outcomes) which we In simple terms outcomes are similar to sub components of a grade. A grade is an assessment of overall performance that may include tests, participation, attendance and projects. Outcomes assess specific levels of knowledge through a series of statements, that maybe coded with numbers or letters. Thus an overall grade can be given for a course, along with statements about specific competencies in the form of outcomes. <br />
we studied that administration can setup framework then can add competencies to them. In this administrator can create the learning plan, add competencies to that plan and then assign to particular selected individual or to whole organisation. <br />
After this i can study about competency framework. the teacher add the competence framework and competence in course and activity.teacher views the breakdown from the **site Administration** and rate the competence rate like competent , just competent, excellent.
> we are adding competencies to ***competence Framework*** we can add competence  like manully,import and export. It support .csv file. 
### April-17-2020.
Competency: It describes the desired knowledge, skills and behaviour of an individual graduating from course. Competencies generally defines the applied skills and knowledge that enable the individual to successfully perform in professional and educational contexts. For the educational point these are added by the teacher to the particular course or to particular activity.

Course Outcome: This is the specific statement that describes exactly what the student will able to gain or do in measurable way. There may be more than one outcome defined for given competency. These are the basics for an assessment program that focuses on what student should be able to do after compeletion of the course.

Lets take example of our course Computer Architecture And Microprocessor: In this teacher has defined competencies and course outcomes for the students.

Let's take that competency is Self Awareness: It describes the student leaders develop thorough understanding of themselves across multiple dimensions. Through different activities, they recignise how their leadership practice and beliefs are influenced by their values and how there behaviour affect their ability to lead.

Course Outcome: The students which demonstrate competency in self-awareness can define their personal values, describe their leadership, strenghts and limitations, evaluate and reflect on their actions and modify as necessary.
### April-18-2020.
Calculation of attainment for practice session. which we study about grade report as well as outcome report.
### April-19,20-2020
complete The spreadsheet of all tables related to attainment.
### April-21,22-2020.
sorry for last two or three days, in two days,introduction about development in moodle.
like what are the required skills and which language used in moodle 
in plugin development we. study types of plugin like activity module,related to Assignment module ,related to Quiz module and all module reports plugin. trying to understand the code of activity module in /mod directory and file structure introduction about blocks development, themes, course format. 
  

