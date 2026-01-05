# Construction Project Management System

## Description  
DBMS project with CRUD operations for managing construction site details (employees, materials, projects) built using PHP & MySQL.

## Features  
- Manage **Employees**: Create, Read, Update, Delete  
- Manage **Materials**: Create, Read, Update, Delete  
- Manage **Projects**: Create, Read, Update, Delete  
- Simple user interface with HTML & CSS  
- Back-end using PHP and MySQL database

## Technology Stack  
| Technology         | Description                            |
|--------------------|----------------------------------------|
| PHP                | Server-side scripting                   |
| MySQL              | Database management system              |
| HTML / CSS         | Front-end layout and styling            |
| MySQLi             | PHP extension for database connectivity |

## Installation & Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/adityaff10/construction-project-management.git

2. **Navigate to the Project Directory**
   ```bash
   cd construction-project-management
   
3. **Set Up the Database**
  
  -  Create a database named construction_db.
  - Import the SQL file located in the database folder:
    ```sql
       mysql -u your-username -p construction_db < database/construction_db.sql

4. **Configure the Database Connection**

  - Update the dbconfig.php file with your database credentials:
    ```php
    <?php
        $servername = "localhost";
        $username = "your-username";
        $password = "your-password";
        $dbname = "construction_db";
    ?>

5. **Start the Server**

 - If you're using XAMPP, move the project folder to the htdocs directory.
 - Start the Apache and MySQL services from the XAMPP control panel.
 - Access the project in your browser at http://localhost/construction-project-management.

## Usage
- Home Page: Provides an overview of the system.
- Projects: View and create new projects.
- Materials: Manage materials used in the projects.
- Employees: Add and view employee details.

## Contributing
  We welcome contributions to enhance the functionality and user experience of this project. Here are some ways you can contribute:

  Report bugs and suggest features via Issues.
  Fork the repository, make your changes, and submit a pull request.
