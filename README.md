|||    Employee Database App (Java + MySQL + JDBC)    ||| 

📌 Overview...
This is a simple Java console application that connects to a MySQL database using JDBC and performs basic CRUD operations:|

Add Employee|
View Employees|
Update Employee|
Delete Employee|

.......................................................................

🛠 Tech Stack...|

Java 21|
MySQL 8+|
MavenJDBC (PreparedStatement, ResultSet)|

........................................................................

CREATING TABLE before implementing code...|

CREATE DATABASE employee_db;
USE employee_db;
CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50) NOT NULL,
    salary DOUBLE NOT NULL
);|
.........................................................................|

📖 Example Usage...|

==== Employee Database Menu ====|
1. Add Employee|
2. View Employees|
3. Update Employee|
4. Delete Employee|
5. Exit|
Enter choice: 1   |
Enter name: Rohit Sharma |
Enter salary: 45000  |
Employee added successfully!










