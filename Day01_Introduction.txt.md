**MySQL Introduction:**



**-->FULLSTACK=FRONTEND+BACKEND**



**Frontend:**

\--------------------------------------------------

frontend is a visual and interactive layer of a website or application that helps users to directly see and interact with a webserver or mobile apps etc.

It is also called the client side because it runs on the users device(browser/mobile).



Responsibilities of Frontend:

\--------------------------------

1.Display web pages and user interface(UI)

2.accepts user input(forms ,buttons ,search boxes)

3.valiadates user input before sending it to the server

4.calls backend API to fetch or send data

5.display the response received from backend

6.Provides animation and interactive effects



To prepare frontend layer we are using some technologies like HTML ,CSS , JS ,Bootstrap.



**Backend:**

\---------------------------------------------------------

Backend is the server-side part of an application.

users cannot see it directly, but it performs all the business logic, security, data processing, and database operations.

It acts as the brain of the application.



Responsibilities of Backend.

\-------------------------------------

* process clients request.
* implements business logic.
* connect with database.
* perform CRUD operations.
* Authenticate and authorize users.
* Encrypts passwords and Authorize users.
* generate reports.
* returns responses to the frontend.
* we have some lang to build backend like java , python, .net, php,c++.



**API(Application Programming Interfaces):**

\-------------------------------------------------------------------------------

API is a set of rules and protocols that allows two different applications or systems to communicate and exchange data without exposing their internal implementation.

It acts as bridge between the frontend and backend bw two different software systems.



Advantages of API's:

\---------------------------------------------------------------------------------

* Enables communication between different systems.
* promotes code reusability.
* platform independent.
* faster application development.
* supports integration with third-party-services.
* improves scalability.
* easy to maintain.



**Storage Areas:**

\-----------------------------------------------------------------------

As part of our applications we request to store data like customers info , billing info, calls info etc... To store these data we require some storage Areas.

There are 2 types of storage areas such as



1)Temporary Storage Areas.

\---------------------------------------------------------------------

These are the memory areas where the data will be stored temporarily.

eg: All PVM memory areas(like heap, Stack, method area, pc, registers, native method stack).

once the PVM is shutdown all these memory areas will be cleared automatically.



2)Permanent Storage Areas:

\------------------------------------------------------------------

It is also known as persistent storage areas. Where data will be stored permanently.

eg: FileSystems, Databases, Dat Warehouse...etc





**File Management Systems(FMS):**

\---------------------------------------------------------------------

A FMS is a system where data is stored in files on the operating systems. Each application program must handle it's own storage data. Retrieval and updating File systems can be provided by the local operating Systems.

File systems are best suitable to store very less amount of information.

Eg: A library management system, storing books in a separate txt files like books.txt, members.txt ... etc.



Limitations of FMS:

\-------------------------------------------------------

1. Data Redundancy: Same data is stored in multiple files.
2. Data Inconsistency: Updates in one file may not be reflected in another
3. Poor Data Security: No proper accessed control.
4. Difficult Data Retrieval: Searching requires custom programs.
5. Integrity Issues: No constraints (ex: rollNum uniqueness).
6. Scalability issues: Hard to manage as data grows.



To overcome the above problems in FMS we should go for databases.



**Data Base Management System(DBMS):**

\--------------------------------------------

&#x20;A DBMS is a collection of programs that enables users to create , manage , manipulate databases.

It acts as an interface between user and database.



Advantages:

\--------------------------------------------------

1. we can storage huge amount of information in databases.
2. Query lang support is available for every database and hence we perform database operations easily.
3. to access data present in the database. Compulsory username and pwd required hence data is secured.
4. Inside database data will be stored in the form of tables. While developing database table schemas, database admin follows various normalization techniques and we can implement various constraints like unique Key ,Primary key ,Foreign key... etc. Which prevent data duplication. Hence there is no chance off data inconsistency problems.



Limitations of databases:

\---------------------------------------------

1.databases cannot store huge amount of information like(terabytes).

2.database can provide support for only structured data(tabular form or relational data) and cannot provide supports for unstructured data or semi-structured data(like videos , audios, xml data).



To overcome these problems we should go for some more advanced databases like data warehouses, big data..etc.



**FMS vs DBMS** 

\--------------------------------------------

























































































