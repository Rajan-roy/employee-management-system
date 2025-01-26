# Employee Management System

This is a Java-based Employee Management System with a graphical user interface (GUI) using Swing. The system allows users to manage employee data, including adding new employees, and performing login authentication. The system interacts with a MySQL database to store and retrieve employee details.

## Features

- **Splash Screen**: Displays a splash screen when the application starts.
- **Login System**: Allows users to log in with a username and password.
- **Add Employee**: Users can add new employees, including their personal details such as name, date of birth, address, salary, education, etc.
- **Database Integration**: Employee details are stored and managed using a MySQL database.
- **User-friendly Interface**: Provides an easy-to-use interface to manage employee data.

## Technologies Used

- **Programming Language**: Java
- **GUI Framework**: Swing
- **Database**: MySQL
- **Libraries**:
  - `com.toedter.calendar.JDateChooser` for date picking.
  - `JTextField`, `JPasswordField`, `JButton`, `JComboBox`, `JLabel` for GUI components.
  
## Setup Instructions

### Prerequisites

- Java 8 or higher
- MySQL Database
- JDBC MySQL Connector
- IDE (Eclipse, IntelliJ, etc.)

Configure Database
Create a MySQL database named employee_management.
Set up the required tables in the database (e.g., employee, login).
Update the database connection details in the conn class (if not provided).
Compile and Run the Application
Open the project in your IDE.
Build the project.
Run the Splash class to start the application.
The splash screen will appear, followed by the login screen where users can enter their credentials to access the system. After login, users can add new employee details.
