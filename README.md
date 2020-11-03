# Bravo Junior Software Engineer Technical Assessment

## Description
This small scale application utilizes JQuery, JQuery DataTables, Bootstrap, and a mock API to allow the user to view imaginary employees at a  fake company.  The user is able to view the employees in an organized table with pagination and a drop-down menu to view ten employees per page at a minimum.  The user can click on arrows corresponding to column name to sort the table in ascending or descending order by first name, last name, facility name, start date, or starting salary.  The user can also use the search bar above the table on the right to search for any information desired.  The table changes automatically with each character typed into the search bar.

## Table Image


## Running the Application 
### Using Git Bash
1. Click the "Clone or Download" link on GitHub. Copy that URL.
2. Run git clone <github url goes here>
3. Running git clone creates a new directory. You can run an ls and see a new directory (named the same thing as the GitHub repo).
4. cd into the directory that just got created
5. Run git checkout -b <name-of-branch> to create a new branch and switch to it.
6. To view the information from the mock api in the table, cd into the api folder in your branch.
7. Run json-server -w bravo.json -p 8000
