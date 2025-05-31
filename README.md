Run Instructions
Set up the Database

Install MySQL (or your chosen database server) if not already installed.

Create a database named, for example, employee_db.

Execute the SQL script to create the employees table with the required fields (id, firstname, lastname, Gender, Position).

Ensure the database user has appropriate permissions to read and write to this database.

Configure the Database Connection

Open the db class or configuration file where the database connection is initialized.

Update the database URL, username, and password to match your local database setup.

Compile and Run the Java Application

Make sure you have JDK installed and set up properly on your machine.

Import the project into your preferred IDE (NetBeans, Eclipse, IntelliJ) or compile via command line.

Run the main class or the form that starts the application (search class or a main launcher class).

Using the Application

Use the ADD button to insert new employee records.

Use SEARCH with the input field to find employees by first name (supports partial matches).

Use MODIFY to update existing employee details.

Use DELETE to remove employee records.

Use CLEAR to reset the search field and reload the full employee list.

Use BACK to navigate back to the previous menu or exit the application.
