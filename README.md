**Repository Link:**
**PDB Name Created:** uh_pdb_29149
**Issues Encountered:** Yes

**Oracle Pluggable Database Assignment II**
**Overview of Tasks**
This assignment required working with Oracle Database Pluggable Databases (PDB).
The tasks included creating a new PDB, creating and deleting another PDB, accessing Oracle Enterprise Manager, and documenting the work.


**Oracle Environment Used**
    • Oracle Database 21c Express Edition
    • Docker container
    • Ubuntu Linux operating system
    • SQL*Plus for database commands
    • Oracle Enterprise Manager Express (OEM) for monitoring
    
    
**Explanation of Each Task**

**Task 1 – Create a New PDB**
In this task, I created a new pluggable database using the required naming format.
After creating the PDB, I opened it and confirmed that it was working.
Then, I created a new user inside the PDB which will be used for other future classes


**Task 2 – Create and Delete a PDB**
In this task, I created a temporary PDB using the required naming format.
I verified that the PDB was created successfully.
After verification, I deleted the temporary PDB completely using SQL commands.
Then I confirmed that the PDB no longer existed.


**Task 3 – Oracle Enterprise Manager (OEM)**
In this task, I accessed Oracle Enterprise Manager Express using the web browser.
I logged in using administrator credentials.
The dashboard showed:
    • The Oracle environment
    • The created PDB
    • The created user account

    
**Challenges Faced and Solutions**
**OEM Not Opening**
At first, Oracle Enterprise Manager did not open in the browser.
This happened because the HTTPS port was not enabled.


**Solution:**
I enabled the port using SQL commands and verified the Docker port mapping.


**Integrity Statement**
I confirm that this assignment was completed by me.
All commands were executed in my own Oracle environment, and the work submitted is original.
