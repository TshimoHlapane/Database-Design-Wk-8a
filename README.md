# 🏨 Hotel Booking Database

## 📌 Project Description

This project is a relational SQL database system designed to manage hotel guest bookings. It includes essential modules for handling guest information, room types, bed types, features, addons, payments, and room status. The system allows for the flexible representation of hotel infrastructure, detailed room classification, and robust booking management.

## 🛠️ How to Run / Set Up the Project

1. Ensure you have MySQL installed.
2. Open a MySQL-compatible tool (e.g., MySQL Workbench, phpMyAdmin, or terminal).
3. Run the SQL script provided in the repository (`hotel_booking_schema.sql`) to create and initialize the database.

### Steps:
```sql
-- Step 1: Create the database
CREATE DATABASE IF NOT EXISTS hotel;

-- Step 2: Select the database
USE hotel;

-- Step 3: Run the remaining CREATE TABLE statements to build the schema

Relationships (1-1, 1-M, M-M where needed)

## 🗂️ Entity-Relationship Diagram (ERD)

If no ERD exists, you can create one using tools like dbdiagram.io, DrawSQL, or MySQL Workbench.
Alternatively, view it here: Link to ERD (Replace with actual link if hosted online)

📋 Tables Included

guest
payment_status
booking
addon
booking_addon
bed_type
room_class
feature
room_class_feature
room_class_bed_type
room_status
floor
room
booking_room
Each table includes primary keys and foreign keys where applicable to maintain normalization and data integrity.

🧠 For Question 1:

Only one .sql file (well-commented)