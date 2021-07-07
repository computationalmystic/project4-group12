# Max to-do list for project 4
1. start by creating the underlying entities as they are represented in the data layer
    - course
    - section
    - assignment
    - submission
    - section membership (not an entity but a relation. doesnt need to be a class)
    - student
    - TA
    - Instructor

2. translate the entities to classes, reverse order of "member of" properties to "get" methods as needed
     ## start with the non-user objects and work up in order of relation
    1. course
        - properties
        1. Instructor (created by)
        2. Course Name
        3. Course Number
        4. semester (includes year)
        5. course description
        - methods
        0. construct(identifying information) creates instance w/other properties
        1. get/set all properties 
        2. C/R section (section params)
        3. C/R course assignments
        4. Get enrolled students (incl. section)
        5. Get list of TAs
    2. section 
        - properties
        1. Section number
        2. Course
        3. time
        - methods
        1. read and update properties
    3. assignment
        - properties
        1. Course
        2. Name
        3. Description
        4. Date assigned
        5. Due date
        - methods
        1. construct(identifying information)
        2. read and update properties
        3. read all submissions
    4. submission
        - properties
        1. Student
        2. Assignment
        3. Score
        4. Date submitted
        5. File
        6. Graded by
        - methods
        1. construct(identifying information)
        2. read and update properties
        3. retrieve submission file
        4. submit the.. submission, upload?
    5. User
        - properties
        1. name
        2. pawprint
        3. dates active
        4. courses
        - methods
        1. read and update properties
        2. login
        3. logout
    6. Student (a user)
        - properties
        1. type (is student)
        - methods (not activities)
        1. get upcoming assignments
        2. get past assignments
        3. open/view assignment submission 
    7. TA (a user)
        - properties
        - methods (not activities)
        1. read assignments to be graded
        2. grade/score assignment
        3. read students and sections
    8. Instructor (a user)
        ### a lot of this class's functionality is embedded in course
        - properties
        - methods (not activities)
        1. assign TAs to courses
        2. read assignments
        3. grade assignments
        4. read students and sections
   

## For a web app I guess I'd tie the page/navigation logic to whatever entitiy being dealt with at the time. Example: course class wouldprovide necessary information to whatever router/controller in order to construct a page. There would be additional classes not listed above to implement a controller and view but those can be technology dependent. 

## requirements document referenced:
# Max to-do list for project 4
1. start by creating the underlying entities as they are represented in the data layer
    - course
    - section
    - assignment
    - submission
    - section membership (not an entity but a relation. doesnt need to be a class)
    - student
    - TA
    - Instructor

2. translate the entities to classes, reverse order of "member of" properties to "get" methods as needed
     ## start with the non-user objects and work up in order of relation
    1. course
        - properties
        1. Instructor (created by)
        2. Course Name
        3. Course Number
        4. semester (includes year)
        5. course description
        - methods
        0. construct(identifying information) creates instance w/other properties
        1. get/set all properties 
        2. C/R section (section params)
        3. C/R course assignments
        4. Get enrolled students (incl. section)
        5. Get list of TAs
    2. section 
        - properties
        1. Section number
        2. Course
        3. time
        - methods
        1. read and update properties
    3. assignment
        - properties
        1. Course
        2. Name
        3. Description
        4. Date assigned
        5. Due date
        - methods
        1. construct(identifying information)
        2. read and update properties
        3. read all submissions
    4. submission
        - properties
        1. Student
        2. Assignment
        3. Score
        4. Date submitted
        5. File
        6. Graded by
        - methods
        1. construct(identifying information)
        2. read and update properties
        3. retrieve submission file
        4. submit the.. submission, upload?
    5. User
        - properties
        1. name
        2. pawprint
        3. dates active
        4. courses
        - methods
        1. read and update properties
        2. login
        3. logout
    6. Student (a user)
        - properties
        1. type (is student)
        - methods (not activities)
        1. get upcoming assignments
        2. get past assignments
        3. open/view assignment submission 
    7. TA (a user)
        - properties
        - methods (not activities)
        1. read assignments to be graded
        2. grade/score assignment
        3. read students and sections
    8. Instructor (a user)
        ### a lot of this class's functionality is embedded in course
        - properties
        - methods (not activities)
        1. assign TAs to courses
        2. read assignments
        3. grade assignments
        4. read students and sections
   

## For a web app I guess I'd tie the page/navigation logic to whatever entitiy being dealt with at the time. Example: course class wouldprovide necessary information to whatever router/controller in order to construct a page. There would be additional classes not listed above to implement a controller and view but those can be technology dependent. 

##requirements document referenced:
https://github.com/maxbalk/mb2kb/blob/master/Assignment%204/Assignment%204.pdf