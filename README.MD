## Project Description

This project is a customized version of a course project focused on creating a book store management system. While the core concepts and functionalities align with the course, several key differences and enhancements have been implemented:

### Key Differences

* **Database Technology** :
* **Course** : MySQL
* **This Project** : PostgreSQL
* 
* **Sequelize Usage** :
* **Course** : Utilized Sequelize CLI for database management.
* **This Project** : Configured Sequelize manually, allowing for greater control and customization.
* 
* **User Role Management** :
* **Course** : Roles and permissions were not distinctly managed.
* **This Project** : Added role-based access control:
  * **Admin** : Can perform CRUD operations (Create, Read, Update, Delete).
  * **Cashier** : Can only view transactions.
  * 
* **Transaction Features** :
* **Course** : Included comprehensive transaction management features.
* **This Project** : Simplified transaction functionality, focusing on essential operations while ensuring that the core features work correctly.
* 
* **Logging** :
* **Course** : Used Morgan for logging HTTP requests.
* **This Project** : Implemented Winston for advanced logging capabilities, offering more flexibility and control over logging levels and formats.
* 
* **Validation** :
* **Course** : Validation methods were not specifically detailed.
* **This Project** : Utilizes JOI for schema validation, ensuring robust and consistent input validation throughout the application.

### Overview

The project is designed to manage book transactions efficiently, supporting administrative functions and basic cashier operations. The choice of PostgreSQL and manual Sequelize configuration reflects a tailored approach to database management, while Winston enhances the logging capabilities compared to the course’s implementation with Morgan. Additionally, JOI is employed for validation, adding an extra layer of reliability to the application's data handling.

Feel free to explore and contribute to the project! If you have any questions or suggestions, don’t hesitate to reach out.



Documentation in POSTMAN
https://documenter.getpostman.com/view/27969319/2sAXqp9j5z
