# REST API for Online Plant Nursery Management
The main objective this Online plant nursery management project is to build a system that will help customers to view available plants, seeds, planters with details and also they can place orders. Admin can perform CRUD operations on plants, seeds, and planters.

Online Plant Nursery Management System is a Spring-Boot project Backend based application.

This is a Group project executed in 5 days with 5 members of team.
- This project is developed by team of 5 Back-end Developers during project week in Masai School.
## Tech Stack
- Java
- Spring Framework
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
## Modules
![Modules](https://user-images.githubusercontent.com/104290715/236598961-e6e895fb-606c-42e3-8d96-d6176b29c24d.png)

- Login, Logout Module
- Admin Module
- Plants Module
- Planters Module
- Seeds Module
## Features
- User and Admin authentication & validation with session uuid.
### Admin Features:
* Administrator Role of the entire application
* Only  admins can add/update/delete plants, planters, seeds from main database
* Admin can access the details of different users and orders.
### User Features:
* Registering themselves with application, and logging in to get the valid session token
* Viewing list of available plants, planters, seeds and order items of them.
* Only logged in user can access his orders, profile updation and other features.
## Contributors
- @Sangram Keshari Sahu
- @Jai Phookan
- @Prashant Bharate 
- @Swapnil Nawgire
- @ Mohammad Ashique Usmani
## Installation & Run
- Before running the API server, you should update the database config inside the application.properties file.
- Update the port number, username and password as per your local database config.
    server.port=8886

    spring.datasource.url=jdbc:mysql://localhost:3306/plantdb
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.username=root
    spring.datasource.password=root

API Root Endpoint
https://localhost:8886/

http://localhost:8886/swagger-ui/



# ER DIAGRAM OF PLANT NURSERY MANAGEMENT APPLICATION


![ER Diagram of Plant Nursery Project](https://user-images.githubusercontent.com/101380040/193456250-c8fea983-dd1c-4888-a967-94ebfad02748.jpeg)

