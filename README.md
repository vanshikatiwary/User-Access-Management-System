User Access Management System
=============================

📌 Description:
This is a web-based application that allows users to sign up, log in, request access to software, and allows managers/admins to approve or manage software.

🛠 Technologies Used:
- Java Servlets
- JSP (JavaServer Pages)
- PostgreSQL Database
- Apache Tomcat (local deployment)

🔐 User Roles:
1. Employee – Can sign up and request access
2. Manager – Can log in and approve/reject requests
3. Admin – Can log in and add new software

📁 Folder Structure:
- src/main/java/servlets/ → All servlet Java files
- src/main/webapp/ → All JSP pages
- schema.sql → Contains table creation and sample insert scripts

💡 How to Run:
1. Import the project in Eclipse (Dynamic Web Project)
2. Add PostgreSQL JDBC JAR to build path and WEB-INF/lib
3. Run Apache Tomcat server
4. Visit: http://localhost:8080/UserAccesManagement/signup.jsp
5. Use `schema.sql` to create required tables in PostgreSQL before testing

🧪 Sample Users (Optional):
- You can pre-insert manager/admin users in `users` table manually if needed.

👩‍💻 Submitted by:
Vanshika Tiwari
