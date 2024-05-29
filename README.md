
# Academia Portal - Course Registration System

**Key Objectives and Functionalities:**

*User Management and Authentication*:
Users (students, faculty, and administrators) access their accounts through a secure login system.
Administrator manages user accounts and ensures authorized access.

*Role-based Access Control*:
Roles include Faculty, Student, and Admin, each with specific privileges and functionalities.

*Administrative Control*:
Admin access is password-protected to prevent unauthorized access.
Admin has functionalities such as adding students/faculty, managing enrollments, and updating user details.

*Student Functionality*:
Students can enroll in new courses, unenroll from existing courses, view enrolled courses, and change passwords.

*Faculty Functionality*:
Faculty members can add new courses, remove offered courses, view enrollments, and change passwords.
Limited seats for courses are assumed.

*Concurrency and Data Protection*:
Read locks and write locks are utilized to protect critical data sections.Socket programming enables the server to maintain the database and serve multiple clients concurrently.

*System Calls Usage*:
System calls are prioritized over library functions for various operations including process management, file management, file locking, semaphores, multithreading, and inter-process communication mechanisms.

**Project Structure:**

*Server-client Architecture*: The server hosts the database and serves multiple clients simultaneously.

*File-based Storage*: Student, faculty, and course information are stored in files.

*Menu-driven Interfaces*: Users interact with the system through intuitive menu-driven interfaces tailored to their roles.

*Socket Programming*: Enables communication between the server and clients, facilitating secure access to academic details.

**Technologies and Implementation:**

*Language and Environment*: Implemented in a suitable programming language (e.g., C/C++) with an emphasis on system calls.
Socket Programming: Utilized for network communication and concurrency management.

*File Management*: System calls for file operations ensure efficient data handling and storage.

*Security Measures*: Password-protected access and role-based authentication mechanisms enhance system security.
