# Employee Database App

## Overview

The **Employee Database App** is a simple Java console application that allows you to manage employee records using a **MySQL database**. You can **add, view, update, and delete employees** through a menu-driven interface.

## Features

* Add Employee
* View Employees
* Update Employee
* Delete Employee
* Exit

## Technologies Used

* Java (JDK 8 or higher)
* MySQL
* JDBC

## Setup Instructions

1. Create a database `employee_db` in MySQL.
2. Create a table `employees` with columns `id`, `name`, `department`, `salary`.
3. Download `mysql-connector-java-8.1.0.jar` and place it in `lib` folder.
4. Compile the Java program:

   ```
   ```

javac -d bin -cp ".;lib/mysql-connector-java-8.1.0.jar" Employee_Database_App/EmployeeDBApp.java

```
5. Run the program:
```

java -cp "bin;lib/mysql-connector-java-8.1.0.jar" Employee_Database_App.EmployeeDBApp

```

## How It Works
- Connects to MySQL using JDBC.
- Uses PreparedStatement for safe SQL queries.
- Handles adding, viewing, updating, and deleting employee records.
- Supports full names and departments with spaces.

## Sample Output
```

--- Employee Database App ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 1
   Enter Name: Anurag Kumar
   Enter Department: Sales
   Enter Salary: 1000
   Employee added successfully!

```
```
