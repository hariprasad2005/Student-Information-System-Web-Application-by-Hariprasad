# Student Information System

## Overview
The **Student Information System** is a web-based application designed to manage student records, including adding students, recording marks, and viewing student information. It utilizes HTML, CSS, JavaScript, and Java for the backend with database integration.

## Features
- Add new student records
- Update student details
- Record student marks
- View student information
- Database connection for persistent storage

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Java
- **Database:** MySQL (SQL file provided)

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- Java Development Kit (JDK)
- Apache Tomcat or any Java-based web server
- MySQL Database
- Any IDE (Eclipse, IntelliJ IDEA, etc.)

### Steps to Run the Project
1. **Set Up the Database**
   - Import `database.sql` into your MySQL server.
   - Update the database connection details in `database-connection.java`.

2. **Deploy the Application**
   - Place the HTML, CSS, and JavaScript files in the appropriate web directory.
   - Compile and run the Java backend using an IDE or command line.

3. **Run on a Web Server**
   - Deploy the project on Apache Tomcat or a similar server.
   - Access `index.html` through a web browser.

## File Structure
- `index.html` - Homepage
- `add_student.html` - Add student details
- `add_marks.html` - Enter student marks
- `view_students.html` - View student records
- `script.js` - JavaScript functions
- `styles.css` - Stylesheet
- `database-connection.java` - Java file for database connectivity
- `database.sql` - SQL file for database setup

## Usage
1. Open the application in a web browser.
2. Add a new student through the form.
3. Record marks for the student.
4. View student details from the database.

## License
This project is open-source and free to use.

