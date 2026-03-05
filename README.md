# CarRental — ASP.NET Core MVC + PostgreSQL

A car rental management web application built with **ASP.NET Core MVC**, **Entity Framework Core**, and **PostgreSQL**.  
The system manages cars, customers, employees, rental contracts, payments, penalties, and more.  
Authentication is implemented using **ASP.NET Core Identity** with role-based authorization for admin features.

---

## ✨ Features

- **Authentication & Authorization**
  - Register / Login / Logout (ASP.NET Core Identity)
  - Role-based access (Admin-only pages like Employees & Licenses)

- **Car Management**
  - Cars catalog with categories (pricing depends on category)
  - View car details and manage car records

- **Customers & Licenses**
  - Customers linked to a Person profile
  - Driver license records and validation

- **Rental Contracts**
  - Create and manage rental contracts
  - Display contracts with related Customer & Car data

- **Payments**
  - Create / list / view payment details
  - Simple payment CRUD flow

---

## 📌 Business Rules (from docs)

- Customer must have a valid driver’s license.
- Customer must be at least 21 years old.
- Customer must provide phone number and national ID.
- Customer cannot rent more than 2 cars at the same time.
- Each car must have a unique plate number.
- Car pricing depends on category.
- Cars cannot be rented if under maintenance.
- Maintenance every 10,000 km.
- Track mileage before & after each rental.
- Track fuel level before & after each rental.
- Contract must have start/end date and end date cannot be before start date.
- Rentals max 30 days unless admin approval.
- Late returns add 20% surcharge per day.
- Damage fees apply.
- Monthly rentals receive 10% discount.
- Employees must log in to create rental contracts.
- Only admins can add/delete cars.

---

## 🧰 Tech Stack

- **C# / .NET (ASP.NET Core MVC)**
- **Entity Framework Core**
- **PostgreSQL**
- **ASP.NET Core Identity**
- **Bootstrap / Static files** (wwwroot)
