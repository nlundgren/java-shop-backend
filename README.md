# JAVA-SHOP

## Project Description

Items shop with login portal and CRUD product functionalities

## Technologies Used

* Java Spring Boot backend
* SQL db 
* JavaScript Angular frontend

## Features

List of features ready and TODOs for future development
* CRUD for products
* Login as Customer or Employee
* Checkout as Customer
* Add product as Employee


## Getting Started
   
`git clone https://github.com/nlundgren/java-shop-backend`

- create application.properties file in the backend under resourses folder:
```
spring.datasource.url = jdbc:mysql://localhost:3306/item-shop?autoReconnect=true&useUnicode=true&characterEncoding=UTF-8&allowMultiQueries=true&useSSL=false
spring.datasource.username = <your_db user
spring.datasource.password = <your_db_password>
```
run command in terminal:

`mvn spring-boot:run`

