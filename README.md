# week8_assignment-
# Library Management System Database

## Description

This project implements a full-featured relational database for a Library Management System using MySQL. It includes tables to manage authors, publishers, books, library members, book loans, reservations, and fines. The database is designed with proper constraints (Primary Keys, Foreign Keys, NOT NULL, UNIQUE) and relationships (One-to-Many and Many-to-Many) to ensure data integrity and efficient management of library operations.

## How to Run/Setup the Project (or Import SQL)

1.  **Ensure MySQL is installed:** You need to have a MySQL server running on your local machine or a remote server.
2.  **Access MySQL:** You can use a MySQL client like MySQL Workbench, DBeaver, or the command-line client.
3.  **Create a database (optional but recommended):** You can optionally create an empty database named `LibraryManagementSystem` before importing. If you don't, the script will attempt to create it.
4.  **Import the SQL file:**
    * **Using MySQL Workbench:** Connect to your MySQL server, navigate to "File" -> "Open SQL Script...", and select the `library_management_system.sql` file. Then, execute the script by clicking the "Execute" button (lightning bolt icon).
    * **Using Command Line:** Open your terminal or command prompt and run the following command:
        ```bash
        mysql -u <your_username> -p < database_name < library_management_system.sql
        ```
        Replace `<your_username>` with your MySQL username and `<database_name>` with `LibraryManagementSystem` (if you created it beforehand) or you can omit the database name and the script will handle creation. You will be prompted for your MySQL password.

