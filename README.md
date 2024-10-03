![Screenshot 2024-10-03 173629](https://github.com/user-attachments/assets/864533d8-8945-4c29-ba46-b5c7b4c64d86)# Assignment-I

# Oracle SQL Database Management Project

# Problem Statement
This project simulates an **Employee Management System** that tracks employees, departments, and project assignments. The database consists of four primary tables: `Departments`, `Employees`, `Projects`, and a many-to-many relationship table `Employee_Project` to manage the assignments of employees to multiple projects. The purpose of this database is to effectively manage employee information, departmental organization, and project participation within an organization.

## System Overview
The system implements the following features:
1. **Employee and Department Management**: Each employee is assigned to a department.
2. **Project Management**: Employees can be assigned to multiple projects, and projects can have multiple employees working on them.
3. **Database Operations**: The system supports data creation, updates, and retrieval using SQL commands.

# SQL Commands Executed

# 1. Table Creation
The following SQL commands were used to create the necessary tables in the database. These commands define relationships between the tables such as:
- One-to-Many (Departments to Employees)
- Many-to-Many (Employees to Projects via the `Employee_Project` table)

![Screenshot 2024-10-03 172846](https://github.com/user-attachments/assets/f8da990d-f68c-4fdc-95d0-725262a81dd7)

# 2. Inserting Data
Sample data was inserted into the tables to simulate real-world entities such as employees, departments, and project assignments:

![Screenshot 2024-10-03 173855](https://github.com/user-attachments/assets/dc53a38d-eaa0-45a1-822c-5814d3671b75)


# 3. Updating Data  and Deleting
We updated employee details to demonstrate how modifications can be made within the system:

![Screenshot 2024-10-03 174101](https://github.com/user-attachments/assets/c95c6950-4788-4f2d-91c5-5d93efe4071c)

# 4. Joins to Retrieve Data
Data from multiple tables was retrieved using SQL joins to provide a comprehensive view of employees and their respective projects:

![Screenshot 2024-10-03 174206](https://github.com/user-attachments/assets/d39a99c2-ea37-4fa6-bdcc-42ec7ca46225)

# 6. DDL, DML, DCL, and TCL Operations

- DDL: Used to define or alter database structures (e.g., `CREATE`, `ALTER`, `DROP`).
- DML: Used to manage data within tables (e.g., `INSERT`, `UPDATE`, `DELETE`).
- DCL: Used to grant or revoke privileges (e.g., `GRANT`, `REVOKE`).
- TCL: Used to manage transactions (e.g., `COMMIT`, `ROLLBACK`).

# 7. Subqueries
An example of a subquery used to find employees working on more than one project:

![Screenshot 2024-10-03 174403](https://github.com/user-attachments/assets/94a919a4-a6ce-4b94-aaff-3f808e3e55fb)
1. Conceptual Diagram:
   - ![Screenshot 2024-10-03 173629](https://github.com/user-attachments/assets/b9234023-25af-45af-bba3-95dc187f700f)

