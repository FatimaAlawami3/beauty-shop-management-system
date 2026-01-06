# Beauty Shop Management System (Java & SQL)

## Overview

This project is a **Beauty Shop Management System** developed using **Java** and a **relational SQL database**. The system is designed to manage the main operations of a beauty shop, including customers, employees, products, sales, carts, payments, and user registration.

The project is uploaded to GitHub as:

* A **Java application packaged as a ZIP file** (NetBeans project)
* A set of **SQL scripts** that define the database schema

This approach preserves the original project structure while keeping the repository organized and easy to understand.

---

## Problem Statement

Managing a beauty shop involves handling multiple interconnected entities such as customers, employees, products, and transactions. Without a proper system, this data can become inconsistent and difficult to manage.

This project provides a structured solution by combining:

* A Java-based application layer
* A relational database backend

to ensure **data consistency, organization, and efficient management** of shop operations.

---

## System Features

The system supports the following core functionalities:

* Customer registration and management
* Employee and manager management
* Product catalog management
* Shopping cart handling
* Sales and transaction recording
* Payment management

Each functionality is backed by a corresponding table in the database and integrated into the application logic.

---

## Database Design

The database follows a **relational design**, where each major entity is represented by its own table.

### Main Tables

* **Customer** – customer information
* **Employee** – employee details
* **Manager** – manager records
* **Products** – beauty shop products
* **Cart** – shopping cart data
* **Sales** – completed sales transactions
* **Payment** – payment records
* **Register** – user registration data

The SQL scripts are provided separately to clearly show the database structure and relationships.

---

## Technologies Used

* **Java** – application logic
* **SQL** – database design and queries
* **NetBeans IDE** – project development
* **Ant** – build configuration

---

## Project Structure

```
beauty-shop-management-system/
├── app/
│   └── BEAUTYSHOP.zip
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

1. Download and extract `BEAUTYSHOP.zip`.
2. Open the extracted project in **NetBeans IDE**.
3. Create a database using your preferred SQL server (e.g., MySQL).
4. Execute the SQL scripts in the `database/` folder to create the required tables.
5. Update database connection settings in the Java project if needed.
6. Build and run the project from NetBeans.

---

## Learning Outcomes

Through this project, the following skills were developed:

* Designing relational databases from system requirements
* Writing SQL scripts for real-world entities
* Integrating Java applications with databases
* Organizing and managing a medium-scale software project

---

## Future Improvements

* Unzip and restructure the application source code directly in the repository
* Add a graphical user interface (GUI)
* Improve validation and error handling
* Extend the system with reporting and analytics features
