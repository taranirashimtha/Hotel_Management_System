Hotel Booking System

Overview
The Hotel Booking System is a Java-based application designed to manage hotel reservations, customer details, room availability, and booking processes efficiently. This system utilizes JavaFX for the user interface, MySQL for database management, and JDBC for database connectivity. Additionally, an Email API can be integrated to send booking confirmations.

Features
Room Management: Add, update, and manage room details.
Customer Information: Store and retrieve customer details.
Reservation Management: Handle booking processes, check room availability, and confirm reservations.
Booking Confirmation: (Optional) Send confirmation emails to customers.
User Authentication: Secure login for managers and staff.
Employee Management: Manage staff records and responsibilities.
Pickup Service Management: Schedule and coordinate customer transportation.

Required Modules and Packages

Core Requirements:

Java SE (Standard Edition) – Core Java for development.
JavaFX – GUI framework for building the interface.
MySQL – Relational database for storing booking data.
JDBC (Java Database Connectivity) – API for connecting and executing queries with MySQL.
Email API (Optional) – For sending booking confirmation emails.

Setup Instructions

1. Database Setup

Install MySQL and create a database named hotel_booking_db.

2. Java Project Setup

Create a new Java project in IntelliJ IDEA or Eclipse.
Add the necessary libraries:
JavaFX SDK
MySQL Connector JAR
Establish a database connection using JDBC.

3. Running the Application

Implement the GUI using JavaFX.
Run the project in your IDE.
Use the application interface to interact with the system (e.g., add rooms, book rooms, manage customer details).

Project Structure

The project consists of multiple Java classes, each handling a specific functionality:
HotelManagementSystem.java – Main entry point of the application.
Dashboard.java – Graphical interface for system navigation.
Login.java – Secure login functionality.
AddRooms.java – Handles adding and updating room details.
AddCustomer.java – Manages customer details.
Booking.java – Manages room reservations.
CheckOut.java – Handles customer checkouts and billing.
CustomerInfo.java – Stores and retrieves customer data.
EmployeeInfo.java – Manages hotel employee records.
PickupService.java – Schedules and tracks pickup services.
Reception.java – Manages front desk operations.
SearchRoom.java – Searches for available rooms.
UpdateRoomStatus.java – Updates room status based on bookings.
DatabaseConnection.java – Handles MySQL database connectivity.

Future Enhancements

Payment Integration: Add online payment options.
Advanced Room Filters: Allow filtering by amenities, price, and occupancy.
Automated Reports: Generate reports for reservations, revenue, and occupancy.
Mobile App Integration: Expand the system with a mobile version.

Author: Tarani Rashmitha Appari
contact : taraniappari@gmail.com
