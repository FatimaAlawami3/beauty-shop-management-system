# Beauty Shop Management System (Java & SQL)

## Overview

This project is a **Beauty Shop Management System** developed using **Java** with a **relational SQL database**. The system is designed to manage the core operations of a beauty shop, including customers, employees, products, sales, carts, payments, and user registration.

The project combines:

* **Application-level logic** implemented in Java (NetBeans project)
* **Database design and implementation** using SQL

It was developed as a **course project** to demonstrate practical skills in **database modeling, SQL, and system integration**.

---

## Problem Statement

Beauty shops handle multiple daily operations such as:

* Managing customers and employees
* Tracking products and services
* Recording sales and payments
* Handling shopping carts and transactions

Manually managing these operations can lead to errors and inefficiency. This project addresses the problem by providing a structured system backed by a relational database to ensure **data consistency, organization, and scalability**.

---

## System Features

The system supports the following core functionalities:

* Customer registration and management
* Employee and manager data management
* Product catalog management
* Shopping cart handling
* Sales transaction recording
* Payment processing

Each feature is mapped to a dedicated database table and integrated into the Java application.

---

## Database Design

The database is designed using a **relational model**, where each major entity in the system is represented by a separate table.

### Main Tables

* **Customer** – stores customer information
* **Employee** – stores employee details
* **Manager** – stores manager-specific data
* **Products** – stores beauty shop products
* **Cart** – manages customer shopping carts
* **Sales** – records completed sales
* **Payment** – stores payment details
* **Register** – handles user registration data

Relationships between tables ensure data integrity and proper linkage between customers, orders, and payments.

---

## Technologies Used

* **Java** – application logic
* **SQL** – database schema and queries
* **NetBeans IDE** – project development
* **Ant** – project build configuration

---

## Project Structure

```
beauty-shop-management-system/
├── app/
│   ├── src/
│   ├── test/
│   ├── build.xml
│   └── manifest.mf
│
├── database/
│   ├── beauty_cart.sql
│   ├── beauty_customer.sql
│   ├── beauty_employee.sql
│   ├── beauty_manager.sql
│   ├── beauty_payment.sql
│   ├── beauty_products.sql
│   ├── beauty_register.sql
│   └── beauty_sales.sql
│
├── README.md
└── requirements.txt
```

---

## How to Run

1. Import the project into **NetBeans IDE**.
2. Create a database using your preferred SQL server (e.g., MySQL).
3. Execute the SQL scripts inside the `database/` folder to create tables.
4. Update database connection settings in the Java source code if required.
5. Build and run the project using NetBeans or Ant.

---

## Learning Outcomes

Through this project, the following skills were developed:

* Designing relational databases from system requirements
* Writing SQL scripts for real-world entities
* Integrating Java applications with databases
* Organizing and managing medium-scale software projects

---

## Future Improvements

* Add a graphical user interface (GUI)
* Improve input validation and error handling
* Add reporting and analytics features
* Deploy the system using a web-based architecture
