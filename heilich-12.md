# Davin's To-Do List for Project 4

1. Start by creating the base classes for each part of the system and then further create the methods needed in each class alot of the classes will have the same intial starting methods for example logging in and and or viewing assignments



# Students

Methods that should be created in the student class

- Login 
    this method should allow the student to login into to the system if the student doesnt login in correctly it should provide an error message proiding what could be possibly wrong
    - View Assignments 
        this method should allow the student to view assignment instructions depending on when the assignments are released if the assignemnt is not avalible yet it shouldnt be viewable 
        - Submit
        This method is to allow students to submit there work depending on if the assignment is due yet or if its already too late to submit
        # Teacher Assistants
        Methods that should be created in the TA
        - Login 
        this method should allow the TA to login into to the system if the TA doesnt login in correctly it should provide an error message proiding what could be possibly wrong  a simple login system basically
        - View Assignments
        this method should allow the TA to view the overall assignment and requirments that the assignment posses
        - View Student Submissions
        this method should allow the TA to view student submissions for assignments that they are able to view or have control over
        - Student Search
        this method should allow a TA to search for studnets inside a class they are apart of
        # Instructor 
        Methods that should be created in the Instructor Class
        - Login 
        this method shoud allow the Instructor to login into the system and provide an error message if there login is wrong
        - Instructors should have the same privallages and or methods as TA's with viewing and grading assignments along with searching for students
        - Create Course and Course Sections
        this method should allow an instructor to create a course inside the system in which he can also create sub sections of that course to divide their classes up if needed
        - Add / Remove Students and TA's 
        this method should allow the Instrutor to add and remove students and TA's from their courses and course sections as they need to it should also allow them to move them from section to section if they are placed in the wrong section at first
        - Create/Delete Assignemnts
        this method should allow instructors to create assignments that students and TA's can access if they posses the right privalleges
        
        # System Admin
        Methods the system admin should have created
        
        - Create, Edit , Delete Instructors and other users
        this method should allow the system admin to create and remove users as needed a lot like how the instructor can and add and remove people from there class but this is for the whole system
        - System Admin should be able to control any and all other users in the system along with the other users data so they can help instructors or students a like to fix problems that are being had
        
        2. Alot of these clases and methods  tie together so you would have to start with the sys admin i would say and work your way down the hierachy of permissions while  developing so that you can make sure everything is working and you are just adding user permissions along the way with the each method you are creating
