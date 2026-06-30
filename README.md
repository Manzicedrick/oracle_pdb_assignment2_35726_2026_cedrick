# Oracle Pluggable Database (PDB) Administration Assignment

## Student Information

**Name:** Cedrick

**Student ID:** 35726/2026

**Course:** Database Programming



# Assignment Objectives

This assignment demonstrates Oracle Database administration skills by:

- Creating and managing database users.
- Granting user privileges.
- Connecting to the Oracle Pluggable Database.
- Verifying user access.
- Understanding Oracle Pluggable Database (PDB) architecture.


# Oracle Environment

- Oracle Database Version: Oracle Database 21c Express Edition (XE)
- Operating System: Windows 11
- SQL Tool: Oracle SQL Developer



# Tasks Completed

## 1. Connected as SYSDBA

Successfully connected to Oracle Database using the SYS account with SYSDBA privileges.



## 2. Verified Oracle Version

Verified that the installed database is Oracle Database 21c Express Edition (XE).



## 3. Connected to XEPDB1

Connected to the default Pluggable Database (XEPDB1).



## 4. Created a New Database User

Created the following user:

**Username**



Granted the following privileges:

- CONNECT
- RESOURCE
- CREATE SESSION
- CREATE TABLE
- CREATE VIEW
- CREATE SEQUENCE
- CREATE PROCEDURE

Also assigned unlimited quota on the USERS tablespace.


5. Verified the User

Verified that the user exists using:



## 6. Logged in Using the New User

Successfully connected to Oracle SQL Developer using the new user account.

---

# Challenge Encountered

Oracle Database 21c Express Edition (XE) supports only the default Pluggable Database (XEPDB1).

Because of this limitation, the commands required to create additional Pluggable Databases (PDBs) in the assignment are not supported in Oracle XE.

This limitation is part of Oracle XE and not an installation error.

---

# Solution

Completed all tasks supported by Oracle Database XE, including:

- Creating a database user.
- Granting privileges.
- Connecting with the new user.
- Verifying the configuration.

The limitation regarding additional PDB creation has been documented.

---

# Screenshots

The repository contains screenshots showing:

- Oracle version
- User creation
- Granted privileges
- User verification
- Successful login
- Oracle XE environment

---

# Conclusion

This assignment provided practical experience in Oracle Database Administration, including user management, privilege assignment, and Oracle SQL Developer connectivity. It also demonstrated the architectural limitations of Oracle Database Express Edition (XE) regarding Pluggable Database administration.

---

# References

- Oracle Database 21c Documentation
- Oracle SQL Developer Documentation
- Database Programming Course Notes

---

# Academic Integrity Statement

I declare that this assignment is my own original work. All practical tasks were completed by me, and any external resources used have been properly acknowledged.
