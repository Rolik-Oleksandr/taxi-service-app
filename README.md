# 🚕 Taxi service app
## 📄 Project description:
 Simple web app that supports user register and authentication and have basic CRUD operations. 
 You could create a car with a driver and connect them, you can also manage who is car driver and adding or removing him  
Created using in-build java functionality sql and servlets
## Features
- registration new driver like user
- user authentication
- logout
- create/update/delete driver
- create/update/delete manufacturer
- create/update/delete car
- displaying all drivers/manufacturers/cars

![pic](png/mainMenu.png)

## Technology stack:
Java 11, MySQL 8.0, JSP, Maven, Tomcat 9.0.76

## 📄How to use app
1. Clone this repo to your ide
```
git@github.com:Rolik-Oleksandr/taxi-service-app.git
```
2. Execute queries from init_db.sql to create needed tables and run it.
3. Replace username, password and url in util package, ConnectionUtil class with your own.

![pic](png/util.png)
4. Create new run configuration tomcat_local 
5. Run mvn package command in terminal. 
6. Use application)

4. Create new run configuration tomcat_local 
5. Run mvn package command in terminal. 
6. Use application)
