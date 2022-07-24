#	🚖 TAXI-SERVICE

**A simple web-application that simulates work of a taxi-service. It supports driver authentication and some CRUD operations.**

### 🚦 Features
---
* Driver Registration/Authentication
* Add Driver to a Car
* Delete Driver
* Create/Delete Car
* Create/Delete Manufacturer
* Display All Cars
* Display All Drivers
* Display All Manufacturers
* Display Cars for the Driver

### 🚦 Structure
---
The project includes 3 models (Driver, Car and Car Manufacturer) and  implies 3-tier architecture with next layers:
* DAO
* Service
* Controllers

### 🚦 Technologies used
---
* JDK 11.0.14
* Maven 3.8.4
* Tomcat 9.0.64
* MySql 8.0.22
* JDBC
* Servlet API 4.0.1
* JSP
* JSTL 1.2

### 🚦 How to run
---
**Requirements**
* Make sure you have MySQL and Tomcat Servers installed
* Use Tomcat Server version 9 to run this project

**Instruction**
1. Create schema and tables by running SQL queries from the file 'src/main/resources/init_db.sql'
2. In order to connect to the database, provide: url, username, password and JDBC_driver to the corresponding fields in the file 'src/main/java/taxi/util/ConnectionUtil.java'
3. Add configuration to your local Tomcat Server
4. Run the project
