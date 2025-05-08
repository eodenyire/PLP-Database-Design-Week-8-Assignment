# 🏥 Clinic Appointment Booking System

## 📘 Description

This project is a **Clinic Appointment Booking System** developed using **MySQL**. It simulates a simple and effective way to manage clinic departments, doctors, patients, and their appointment schedules.

The system captures:
- Departmental structure of the clinic
- Doctor assignments per department
- Patient records
- Scheduled appointments between doctors and patients

## 🧠 Project Features

- Normalized database design with 4 main entities: `Department`, `Doctor`, `Patient`, and `Appointment`
- Proper use of primary and foreign keys
- Enforced constraints such as `NOT NULL`, `UNIQUE`, and `AUTO_INCREMENT`
- Clearly defined 1:M relationships

## 🛠️ How to Run/Setup

1. Install MySQL on your local machine or use an online SQL editor.
2. Clone this repository:

   ```bash
   git clone https://github.com/your-username/clinic-booking-system.git
   cd clinic-booking-system
3. Open your MySQL client and import the clinic_system.sql file:
   SOURCE clinic_system.sql;
4. Confirm tables were created:
   SHOW TABLES;
5. You can now insert test data and run queries on the system.
