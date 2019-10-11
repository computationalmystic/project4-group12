# group todo list
1. decide on technology stack set up database on test server and individual environments
2. set up python backend with connection to database and expose API to front end
3. set up web server that can call back end's API
4. create a test database with our set of entities and their constraints
   1. course
   2. section
   3. assignment
   4. submission
   5. section membership
   6. user (specifies type)
5. create code objects in order of most dependencies
   1. user
   2. course
   3. section
   4. assignment
   5. submission
6. start implementing actions in order of importance, including interface
   1. login/logout
   2. open course
   3. submit assignment
   4. instructor admin operations
      1. TA, student and course management
   5. system admin operations
      1. edit instructor data