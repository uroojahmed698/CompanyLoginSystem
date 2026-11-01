Employee Login and Registration System

A Java-based desktop application that provides employee account registration and login functionality, using Java Swing for the graphical interface and SQLite for data storage.

Overview:

The Employee Login and Registration System is a desktop application developed to manage employee account creation and authentication. It allows employees to register using unique registration codes and subsequently log in using their account credentials.

The project demonstrates Java GUI development, database integration, authentication logic, and object-oriented programming.
<img width="1272" height="826" alt="image" src="https://github.com/user-attachments/assets/34c22878-960c-41ce-baaa-4feee950f9c4" />
<img width="1248" height="822" alt="image" src="https://github.com/user-attachments/assets/22e2ddf1-11f5-4744-94e3-4f57fec76061" />
<img width="646" height="417" alt="image" src="https://github.com/user-attachments/assets/cde53c07-895e-482a-a0c0-eb6766794458" />

Features:

Employee Registration: Allows new employees to create accounts using a unique registration code.

Unique Registration Codes: Uses registration codes to authorize account creation.

User Authentication: Validates employee login credentials against stored account information.

Database Integration: Uses SQLite databases to store and retrieve employee account information and registration codes.

Graphical User Interface: Provides interactive desktop interfaces built with Java Swing.

Account Access: Provides a login workflow for registered employees.

Technologies Used:

Java – Application logic and object-oriented programming.

Java Swing – Graphical user interface development using JFrame components.

SQLite – Database management and persistent data storage.

JDBC – Connecting the Java application to SQLite databases.

Eclipse IDE – Project development and debugging.

Project Structure:

CompanyLogin/
├── src/
│   └── login/
│       ├── Authorizor.java
│       ├── Login.java
│       ├── LoginJFrame.java
│       ├── Register.java
│       ├── WelcomePage.java
│       └── sqliteConnectionClass.java
├── EmployeeDatabase.db.db
├── uniqueCodes.db
├── bin/
├── .classpath
└── .project

Getting Started:

Prerequisites -->

Java Development Kit (JDK)

Eclipse IDE (or another compatible Java IDE)

SQLite JDBC support

Installation:

Clone the repository,

git clone https://github.com/uroojahmed698/CompanyLoginSystem.git

Extract the CompanyLoginProject.zip archive.

Open Eclipse IDE.

Import the extracted project as an existing Eclipse project.

Ensure the required libraries and SQLite database files are available in the project.

Run the application starting from WelcomePage.java.

Learning Outcomes: Building desktop applications using Java Swing.

Implementing account registration and login workflows.

Connecting Java applications to SQLite databases using JDBC.

Designing database-backed authentication functionality.

Working with multiple database files.

Organizing Java applications using separate classes and responsibilities.

Debugging and troubleshooting database connectivity and authentication issues.


Author: Urooj Ahmed
