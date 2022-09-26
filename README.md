# **Taxi-service**

## Description:
***This application is a simplified version of the taxi service.***

## Goals:
> - Show the principles of N-tier architecture when designing an application;
> - Show examples of working with a database using JDBC;
> - Show how servlets and filters work.

## Structure:
***The application has an N-Tier Architecture.***

> - Controllers layer - allows this application to communicate with users by receiving requests and sending responses;
> - Service layer - responsible for the business logic of the application;
> - Dao layer - responsible for performing database operations (CRUD operations).

## Futures:

> - Register, login, logout;
> - Create and delete all existing models;
> - Display all existing models;
> - Add a driver to car;
> - Display all cars of the logged-in use;

## Used technologies:
> - Java 11
> - JDBC
> - JSP
> - JSTL
> - Maven 3.10.1*
> - MySQL 8.0.30*
> - Java Servlet API 4.0.1*
> - JSTL 1.2*
> - TomCat 9.0.50*

**You can use other versions, but in this case the correct operation of the program will not be guaranteed.*

## Instruction for launching:
> - Fork this repository;
> - Clone the repository to your PC;
> - Use the init_db.sql file to create the database;
> - Edit ConnectionUtil.class to set the necessary parameters:
> ```
>    private static final String URL = "URL";
>    private static final String USERNAME = "USER NAME";
>    private static final String PASSWORD = "PASSWORD";
>    private static final String JDBC_DRIVER = "JDBC DRIVER";
>   ```
> - Install Tomcat;
> - Edit configurations your local Tomcat server;
> - Run the project.

