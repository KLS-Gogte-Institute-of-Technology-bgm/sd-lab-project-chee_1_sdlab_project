# SRS Document
## Library Management System
#### Functional Requirements
The Librarian does the following function(s):-
- Add Article
 New entries must be entered in database
- Update Article
Any changes in articles should be updated in case of update
- Delete Article
Wrong/Expiry/Un-usable entry must be removed from system
- Inquiry Members
Inquiry all current enrolled members to view their details
- Inquiry Issuance
Inquiry of all database articles

- Check out Article
To issue any article must be checked out
- Check In article
After receiving any article system will reenter article by Checking
- Inquiry waiting for approvals
Librarian will generates all newly application which is in waiting list
- Reserve Article
This use case is used to reserve any book with the name of librarian, it can 
be pledged
- Set user Permission
From this user case Librarian can give permission categorically, also 
enabling/disabling of user permission can be set through this use case.
MEMBER does the following function(s):-
- Authentication
User must authenticated before accessing system
- Search Article
User can search any article
- Request Article
After successful searching member mark this book as requested article
- Check Account
This use case is used to check account details
- Check out Article
To issue any article must be checked out
- Check In article
After receiving any article system will reenter article by Checking
- Inquiry waiting for approvals
Librarian will generates all newly application which is in waiting list
- Reserve Article
This use case is used to reserve any book with the name of librarian, it can 
be pledged
- Set user Permission
From this user case Librarian can give permission categorically, also 
enabling/disabling of user permission can be set through this use case.
MEMBER does the following function(s):-
- Authentication
User must authenticated before accessing system
- Search Article
User can search any article
- Request Article
After successful searching member mark this book as requested article
- Check Account
This use case is used to check account details

#### Non-Functional Requirement
-	Safety Requirements
The database may get crashed at any certain time due to virus or operating 
system failure. Therefore it is required to take the database backup.
-	Security Requirements
We are going to develop a secured database for the university .There are 
different categories of users namely teaching staff, administrator, library 
staff ,students etc., Depending upon the category of user the access rights are 
decided. It means if the user is an administrator then he can be able to 
modify the data, delete, append etc., all other users other than library staff 
only have the rights to retrieve the information about database.
-	Software Quality Attributes
The Quality of the database is maintained in such a way so that it can be 
very user friendly to all the users of the database
-	Hardware Constraints
The system requires a database in order to store persistent data. The database 
should have backup capabilities.
-	Software Constraints
The development of the system will be constrained by the availability of 
required software such as database and development tools.
