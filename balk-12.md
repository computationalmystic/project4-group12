#Max to-do list for project 4
1. start by creating the underlying entities as they are represented in the data layer
    - course
    - section
    - assignment
    - submission
    - section membership
    - student
    - TA
    - Instructor

2. translate the entities to classes, reverse order of "member of" properties to "get" methods as needed
    - start with the non-user objects and work up in order of relation
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
        2. C/R/U/D section (section params)
        3. C/R course assignments
        4. Get enrolled students (incl. section)
        5. Get list of TAs
    2. section
        - properties