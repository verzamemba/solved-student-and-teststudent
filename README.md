Download Link: https://assignmentchef.com/product/solved-student-and-teststudent
<br>
5/5 - (1 vote)

In this task, you are required to provide the definition of a class called Student, which represents a typical (but a very limited) university student. Each student has a name (which consists of a string of characters) and a unique student identification (ID) number (consisting of a string of exactly six numerical digits).



You are also required to define a class called TestStudent, which will be used to perform a number of test used to among other things, verify the correctness of the Student class.

In order to maintain the uniqueness of the student ID, your program will need to check that any new IDs supplied by the user is not the same as any of the existing student IDs.

Following are a list of specifications of the Student class:

Two fields name and id representing the student name and the student ID respectively as described above

Get and set methods for each field (getName(), getId(), setName(), setId())

A toString() method that returns a string description of a given student object

An isValidId() method which accepts a string representing a possible new student ID as an argument and returns a boolean value (true or false) indicating whether the new ID satisfies the structural requirements of the student ID or not

A IdExists() which accepts a string argument representing a possible new student ID and returns a boolean value indicating whether the new ID is already being used by another student or not

Your TestStudent class should be able to perform the following functions:

Create an ArrayList object of Student objects called studentList, using the student data stored in a text file named students.txt (you should create this file such that it stores the student name and ID of several students initially – one line per student)

Allow the user to add as many new Student objects as the user requests to the ArrayList ensuring that each student has a unique student ID

When the user has finished adding new students to the list, the program will override the students.txt file such that it includes the data relating to the new students as well as the original ones

Ability to display a full list of students as well as just the existing student IDs when necessary

Ensure that the program is appropriately documented throughout and thoroughly tested to demonstrate its correct operation.

The data in students.txt is something like…. (firstNAME + lastNAME + ID)

Paul Smith 122345

Mike Fello 123456

Mary Gibson 543213