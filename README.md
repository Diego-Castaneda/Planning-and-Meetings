# Planning and Meetings

## Sprint 1 Planning

Users will work by checking OAuth and then send that username to program and reply with if the exists (404/200)
  * Security Concerns - not something that we really would have to worry about
  * Other options - not really - Look deeper into OAuth and see what they suggest
  
ERD/Database
  * Using none relational database
    * User, jobs, time sheet entries as tables
    * $7/month for database through Firebase
    
Where to format into CSV (Front End/Back End)? Will be a discussion later in the process

Client Questions
  * When uploading csv file with jobs, Is it going to have the old jobs as well? Will it have the jobs such that the jobs correctly point to the old jobs?
      * Insert and avoid duplicates? Put in without references?
  * Is there is an entry for a user and that user is removed, how do we deal with that?
    * Dealing with Node SQL
  * How long should we store the data? Will they want to go back and look at it?
  
