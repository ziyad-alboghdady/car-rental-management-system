# 🚗 Car Rental Management System

A **full-featured web application** built using **ASP.NET Core MVC** that manages the operations of a car rental company.  
The system allows administrators and employees to manage **cars, customers, employees, rental contracts, payments, and licenses** through a structured and secure interface.

The project demonstrates modern backend development practices including **MVC architecture, authentication, database design, and SQL business logic**.

---

## 📌 Project Overview

The **Car Rental Management System** is designed to manage the workflow of a car rental company.

It allows the system to:

- Manage cars available for rent
- Register and manage customers
- Handle rental contracts
- Track payments
- Manage employees
- Validate customer licenses
- Control access through authentication and authorization

The project follows **clean separation of concerns using MVC architecture**.

---

## 🛠 Technologies Used

### Backend

- C#
- ASP.NET Core MVC
- Entity Framework Core
- ASP.NET Core Identity

### Database

- SQL Server
- SQL Scripts
- Tables
- Constraints
- Stored Functions
- Triggers
- Seed Data

### Architecture & Design

- MVC (Model – View – Controller)
- Entity Framework Migrations
- Database Contexts
- Authentication & Authorization

### Development Tools

- Visual Studio
- Git
- GitHub

---

## 🧩 System Modules

The system includes the following modules:

### 🚘 Cars Catalog

Manage all available cars in the system.

**Features**

- Add new cars
- Update car information
- View available cars
- Manage car details

**Controller**


CarsCatalogController


---

### 👥 Customers Management

Handles customer registration and management.

**Features**

- Add customers
- Update customer information
- View customer details

**Controller**


CustomersController


---

### 👨‍💼 Employees Management

Manage company employees.

**Features**

- Register employees
- Update employee information
- Manage employee records

**Controller**


EmployeesController


---

### 📄 Rental Contracts

Handles the core rental operations.

**Features**

- Create rental contracts
- Track rentals
- Manage rental records

**Controller**


RentalContractsController


---

### 💳 Payments

Manage rental payments.

**Features**

- Record payments
- Track payment details

**Controller**


PaymentsController


---

### 🪪 License Management

Manage customer driving licenses.

**Features**

- Store license information
- Validate licenses

**Controller**


LicensesController


---

### 🔐 Authentication & Authorization

The system uses **ASP.NET Core Identity** for:

- User authentication
- Secure login
- Role-based access

**Controller**


AccountController


---

## 🗄 Database Design

The database was designed with proper relational structure and includes:

### SQL Files


db/
01_tables.sql
02_constraints.sql
03_functions.sql
04_triggers.sql
05_seed_data.sql


### Database Features

- Table relationships
- Constraints
- Business logic using triggers
- Custom SQL functions
- Initial seed data

---

## 📊 System Documentation

The project also includes documentation explaining the system design.

**Location**


docs/


**Includes**

- ERD Diagram
- Business Rules
- Requirement Specification

**Files**


car_rental_ERD.drawio.png
business_rules.md
car_rental_textual_RS.pdf


---

## 📂 Project Structure


src/CarRental

Controllers
AccountController
CarsCatalogController
CustomersController
EmployeesController
HomeController
LicensesController
PaymentsController
RentalContractsController

Data
CarRentalDbContext
CarRentalIdentityDbContext
IdentitySeedData

Migrations

Views

Models


---

## ▶️ Running the Project

### 1️⃣ Clone the repository


git clone https://github.com/ziyad-alboghdady/car-rental-management-system.git


### 2️⃣ Open the project

Open the project using:

- Visual Studio

### 3️⃣ Configure the database

1. Create a new SQL Server database  
2. Run the SQL scripts in the **db** folder

Order:


01_tables.sql
02_constraints.sql
03_functions.sql
04_triggers.sql
05_seed_data.sql


### 4️⃣ Run database migrations


Update-Database


### 5️⃣ Run the application

Start the project using:


dotnet run


or run directly from **Visual Studio**.

---

## 🎯 Learning Objectives

This project demonstrates practical experience with:

- ASP.NET Core MVC development
- Entity Framework Core
- Authentication using ASP.NET Identity
- SQL database design
- Business logic with triggers and functions
- MVC architecture
- Full backend system development

---

## 👨‍💻 Author

**Ziyad Alboghdady**

Software Engineering Student

GitHub  
https://github.com/ziyad-alboghdady

LinkedIn  
https://www.linkedin.com/in/ziyad-alboghdady-a50ab8247

---

## 📄 License

This project is created for **educational and learning purposes**.
