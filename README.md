# 🏨 Hotel Booking Database

## 📌 Project Description

This project is a relational SQL database system designed to manage hotel guest bookings. It includes essential modules for handling guest information, room types, bed types, features, addons, payments, and room status. The system allows for flexible representation of hotel infrastructure, detailed room classification, and robust booking management.

## 🛠️ How to Run / Set Up the Project

1. Ensure you have MySQL installed.
2. Open a MySQL-compatible tool (e.g., MySQL Workbench, phpMyAdmin, or terminal).
3. Run the SQL script provided in the repository (`hotel_booking_schema.sql`) to create and initialize the database.

### 🗂️ Entity-Relationship Diagram (ERD)

![ERD Path](/ERD/443536927-4d35f878-512a-4853-8897-41b12be0e8af.png)

### 📊 ERD Description

The Entity-Relationship Diagram (ERD) represents the logical structure of the hotel booking database:

- **Guests** can make multiple **Bookings**, each associated with a **Payment Status**.
- A **Booking** can include multiple **Rooms** and multiple **Addons**.
- **Rooms** belong to a **Room Class**, have a **Status**, and are located on a **Floor**.
- **Room Classes** define pricing, features, and supported bed configurations.
- **Addons** represent optional extras linked to a booking.
