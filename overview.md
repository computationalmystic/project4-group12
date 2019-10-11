# group todo list
1. decide on technology stack 
2. set up database and file storage on test server and individual environments
3. set up python backend with connection to database and expose API to front end
4. set up web server that can call back end's API
5. create a test database with our set of entities and their constraints
   1. course
   2. section
   3. assignment
   4. submission
   5. section membership
   6. user (specifies type)
6. create backend code objects in order of most dependencies
   1. user
   2. course
   3. section
   4. assignment
   5. submission
7. start implementing actions in order of importance, including their interface pages. Actions like "submit assignment" shouldnt be too complicated since we've supposedly layed the groundwork first. 
   1. login/logout. 
      1. might have to add to schema to store passwords.. create additional code objects for authentication steps. 
   2. open course
   3. submit assignment
   4. instructor admin operations
      1. TA, student and course management
   5. system admin operations
      1. edit instructor data
8. Run QA to make sure everything is working as intended
   1. individually and on test server
   2. behavior and stress test (on server)


