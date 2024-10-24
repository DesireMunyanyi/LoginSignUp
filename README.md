# Login Application

This Java Swing application provides a login interface for user authentication against a SQL Server database.

## Features

- User login with email and password.
- Error messages for invalid login attempts.
- Redirects to a welcome screen upon successful login.
- Option to navigate to a sign-up screen.

## Requirements

- Java Development Kit (JDK) 8 or higher.
- Microsoft SQL Server.
- JDBC Driver for SQL Server.

## Database Setup

1. Create a Database: Ensure you have a SQL Server database named signup.
2. Create a Table: Inside the database, create a table called logiinn with the following columns:
   - Email (VARCHAR)
   - Password (VARCHAR)

   Example SQL command to create the table:
   ```sql
   CREATE TABLE logiinn (
       Email VARCHAR(255) NOT NULL,
       Password VARCHAR(255) NOT NULL
   );
