# Week-8-Database-Assignment


Clinic Booking System Database
A MySQL-based database solution for managing medical appointments, patient records, and prescriptions.

Description
This project provides a relational database schema for a clinic booking system, designed to:
Track patient demographics and admission dates.
Manage doctor profiles and specializations.
Schedule appointments with status tracking (Scheduled/Completed/Canceled).
Record prescribed medications and their statuses (Active/Completed/Discontinued).

Setup Instructions
Prerequisites
MySQL Server 8.0+
MySQL Workbench (optional)
Command-line access or GUI tool for SQL execution

Database Structure
ER Diagram
Tables:
Patient: Stores patient details (ID, name, age, contact, admission date).
Doctors: Manages doctor profiles (ID, specialization, contact).
Appointment: Links patients and doctors with time slots and statuses.
Medication: Tracks prescriptions tied to specific appointments.
