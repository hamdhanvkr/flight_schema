# ✈️ Flight Database Schema — SQL Developer Internship Task

This project is part of the **SQL Developer Internship**. It focuses on database schema design, entity relationships, and normalization for a flight booking system.

---

## 📘 Domain: **Flight Booking System**

### 📋 Dataset Fields Used:
- `airline`
- `flight`
- `source_city`
- `departure_time`
- `stops`
- `arrival_time`
- `destination_city`
- `class`
- `duration`
- `days_left`
- `price`

---

## 🗂️ Schema Overview

The database consists of the following tables:
- `Airlines`
- `Cities`
- `Flight_Classes`
- `Flights`
- `Flight_Details`

All primary and foreign keys are properly defined to maintain referential integrity.

---

## 📦 Files Included

| File Name        | Description                             |
|------------------|-----------------------------------------|
| `flight.sql`     | SQL script to create the database schema |
| `er_diagram.png` | ER Diagram of the flight database       |
| `README.md`      | This documentation file                 |

---

## 🔗 Relationships

- `Flights.airline_id` → `Airlines.airline_id`
- `Flight_Details.flight_id` → `Flights.flight_id`
- `Flight_Details.source_city_id` → `Cities.city_id`
- `Flight_Details.destination_city_id` → `Cities.city_id`
- `Flight_Details.class_id` → `Flight_Classes.class_id`

---

## 🎯 Key Concepts Demonstrated

- Database design using **DDL (Data Definition Language)**
- Entity Relationship Mapping (ER Diagram)
- Normalization to remove redundancy
- Use of **Primary Key** and **Foreign Key**
- Basic **INSERT** statements

---

## 📚 Interview Q&A

**1. What is normalization?**  
Normalization is the process of organizing data to reduce redundancy and improve data integrity.

**2. Primary Key vs Foreign Key?**  
- Primary Key: Uniquely identifies each record in a table.  
- Foreign Key: Links one table to another and enforces referential integrity.

**3. What are constraints?**  
Constraints are rules applied to columns (e.g., NOT NULL, UNIQUE, PRIMARY KEY, FOREIGN KEY) to enforce data integrity.

**4. What is a surrogate key?**  
A surrogate key is a unique identifier for an entity, usually auto-incremented and not derived from application data.

**5. How do you avoid data redundancy?**  
By using normalization (1NF, 2NF, 3NF), separating data into related tables with foreign keys.

**6. What is an ER diagram?**  
A visual representation of entities and relationships in a database.

**7. Types of relationships in DBMS?**  
- One-to-One  
- One-to-Many  
- Many-to-Many

**8. Purpose of AUTO_INCREMENT?**  
Automatically generates a unique number when a new row is inserted.

**9. Default storage engine in MySQL?**  
InnoDB

**10. What is a composite key?**  
A primary key made up of two or more columns.

---

## ✅ Status

✔️ Tables Created  
✔️ Data Inserted  
✔️ ER Diagram Generated  
✔️ Files Uploaded to GitHub

---

## 🔗 Submission

GitHub Repository Link:  
===========================
https://github.com/hamdhanvkr/flight_schema



**[Paste your repository URL here]**

