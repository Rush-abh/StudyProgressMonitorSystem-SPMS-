 # Study Progress Monitor System (SPMS)
 Application to manage students’ grades allowing administrators to add students, enrol subjects with
assessments, set grade, and parents/students to access the stored details.
 
 ##### Developed By: 
[Rushabh Pancholi](https://www.linkedin.com/in/rushabh-pancholi-62235b166/), [Abhishek Ejam
](https://www.linkedin.com/in/abhishek-ejam/)

#### Project Definition: 
Application built using conecpts of networking, inter-process communication, remote invocation, efficient algorithms, inheritance, polymorphism,
exception handling and multi threading.

##

<h3>Features of System:</h3>

All users accessing the SPMS should able to view the following data:

1. Register by entering a user name and password
2. Securely login by entering a UserId and Password
3. List of assessments for a chosen subject
4. Grades of assessments for a student

Administrator should be able to access the SPMS to:

1. Set grade for a chosen student and subject
2. Add a student 

##
<h3>HOW TO GET STARTED?</h3>

Step 1: Open two console (terminal)

Step 2: In first terminal: <br>
       <b>type</b> javac -cp . *.java <br>
       <b>type</b> java -cp . Server
       <br>
Step 3: In second terminal<br>
       <b>type</b> java -cp . Client
##

<h3>Application Diagrams:</h3>

Architecture:
User gives input towards client side and sends a request to the server and receives a response. The server interacts with the database to process the request and obtains a result in response. 
<p align="center"><img align="centre" width="600" height="500" src="https://i.imgur.com/nDL0XQb.png"></p> 
<p align="center"><img align="center" width="600" height="400" src="https://i.imgur.com/jHbvYXC.png"></p>
Workflow:
The user starts the application redirected to the login and registration menu. Further, depending on the functionality selection, the action is performed. Further four functionalities are available for operation. Selecting operation 1 user will be prompted to input the subject, recording the input query execution will take place responding the user with the result. Further user will be redirected to the main menu allowing to execute other operation. Like operation 1 the corresponding actions and execution will take place for operation 2, 3 and 4. The new operation 4 is available only for administrator which allows adding the students into system. The operation 5 is exit functionality which can be selected by pressing 0 which, further closes the running application.
<p align="center"><img align="center" width="500" height="500" src="https://i.imgur.com/IKeyusV.png"></p>
Class Diagram:
All the systems classes, their attributes, and methods can be seen in the diagram. Client, Server and DatabaseUtility are major class and other are domain classes. 
<p align="center"><img align="center" width="1200" height="900" src="https://i.imgur.com/p24FBDg.png"></p>

<h3>Application illustration:</h3>

**User registration and login:**
Selecting user registration to register student. Entering passowrd for student. Receiving ID for student.
Selecting login for administrator login. Entering user id and password. Further, receiving main menu.
<p align="center"><img align="center" width="1500" height="300" src="https://i.imgur.com/rjg8Qe7.png"></p>
<p align="center"><img align="center" width="1500" height="300" src="https://i.imgur.com/143oHpD.png"></p>
<p align="center"><img align="center" width="1500" height="200" src="https://i.imgur.com/gpUJiCn.png"></p>

##

**Assessment as per subject:**
Operation selection input and displaying the available subjects.
Subject name input and display result:
<p align="center"><img align="center" width="1500" height="200" src="https://i.imgur.com/uwivIX0.png"></p>
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/bgtJn9p.png"></p>

##

**Grades of assessment as per student:**
Login as admin and view grade of student. Initially select function to view grade. Next, select student whose grade to be displayed. Further, select subject. Upon selecting all things correctly, corresponding grade will be displayed.
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/tWTyzQt.png"></p>
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/Y4ZqZkt.png"></p>

##

**Update grade as per student and subject:**
Selecting the set grade option.
Next, selecting student and subject for which grade need to be updated.
Then, selecting assessment and grade wich needs to be updated. Receiving the success message for setting the grade. 
Lastly, viewing the grade after successfully updating with required steps.
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/mLZmHZn.png"></p>
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/VyINcQT.png"></p>
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/9EDaeKf.png"></p>
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/ssb68g3.png"></p>

##

**Add student (for administrator):**
Selecting the add student functionality from menu. Only available to administrators. Further entering the student name year level in correct format. At least, receiving the success message of adding the student.
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/HqtIIAH.png"></p>

##

**Multi-Threading:**
Thread creation for multiple clients simultaneously:
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/EpTK8w2.png"></p>

##

**Close the application:**
Exiting the client application:
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/bh7PPh8.png"></p>
<p align="center"><img align="center" width="1500" height="400" src="https://i.imgur.com/0Yaaa90.png"></p>
