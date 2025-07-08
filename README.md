# Park@Ease - Smart Parking Lot Management System Using IoT

Welcome to **Park@Ease**, a comprehensive smart parking lot management system designed to streamline parking operations through IoT integration, secure access control, and intelligent subscription and payment management.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Technology Stack](#technology-stack)  
- [Database Schema](#database-schema)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Project Overview

Park@Ease aims to optimize parking lot management by leveraging IoT sensors to monitor parking slot availability in real-time, providing a seamless booking experience, secure access control via RFID/QR, and comprehensive staff and subscription management. This solution benefits both parking lot administrators and customers by improving efficiency, security, and user experience.

---

## Features

- **User Management:** Registration and management of customers and admins  
- **Vehicle Tracking:** Link vehicles to users and track their bookings  
- **Real-Time Slot Availability:** IoT sensors monitor parking slots’ occupancy  
- **Booking System:** Reserve parking slots with flexible time frames  
- **Payment Gateway:** Support for multiple payment methods with transaction tracking  
- **Access Control:** RFID/QR-based authentication for secure entry  
- **Violation Tracking:** Monitor unauthorized or invalid parking attempts  
- **Subscription Plans:** Monthly and yearly parking subscriptions with discount management  
- **Staff Management:** Manage parking lot staff and roles  
- **Audit Logs:** Track changes and actions for bookings, payments, and sensors  
- **Detailed Reporting:** Complex queries for parking trends, violations, and usage  

---

## Technology Stack

- **Database:** MySQL  
- **Backend:** SQL scripts for database schema and complex queries  
- **IoT Integration:** Parking sensors (conceptual - integration depends on hardware and APIs)  
- **Security:** Access tokens with RFID/QR authentication  

---

## Database Schema

The system consists of the following core tables:

- `users`  
- `vehicles`  
- `parking_lots`  
- `parking_slots`  
- `bookings`  
- `payments`  
- `parking_sensors`  
- `access_control`  
- `logs`  
- `violations`  
- `staff`  
- `subscription_plans`  
- `user_subscriptions`  
- `discounts`  
- `booking_discounts`  

Additionally, audit tables are implemented for critical actions on bookings, payments, and parking sensors.

---

## Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/park-at-ease.git
   cd park-at-ease
2.Set up the database

-Import the SQL scripts (database_schema.sql) to your MySQL server:
bash
Copy
Edit
mysql -u yourusername -p < database_schema.sql

3.Configure your backend

Connect your application backend to the ParkinglotMgmtSystem database.

4.IoT Device Integration

Integrate with actual parking sensors and access control hardware via APIs (to be developed separately).

Usage
-Register users and vehicles

-Create parking lots and slots

-Monitor real-time slot availability using sensor data

-Book parking slots and make payments

-Manage staff and subscriptions

-Generate reports using provided complex SQL queries

Thank you for checking out Park@Ease!
