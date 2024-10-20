# Railways Management System

## Project Overview
The **Railways Management System** is a C++ project designed to manage railway operations. It supports three types of users: **Admin**, **Employee**, and **User**, each with specific roles and permissions. The system manages users, trains, routes, and ticket bookings through a command-line interface.

## User Roles and Functionalities

### 1. Admin
- **User Management**: Add, delete, update, view all, and search users.
- **Employee Management**: Add, delete, update, view all, and search employees.
- **Train Routes Management**: Add, remove, and view train routes.
- **Tickets Management**: View and manage details of all booked tickets.
- **View Stats**: Access statistics related to trains, routes, revenue collected and ticket sales.

### 2. Employee
- **User Management**: Add, delete, update, view all, and search users.
- **Train Routes Management**: Add, remove, and view train routes.
- **Tickets Management**: Access details of booked tickets and assist in the booking process.
- **View Personal Data**: Access and review their personal information.
- **Change Password**: Update account password securely.

### 3. User
- **Book Tickets**: Reserve tickets for available routes.
- **Cancel Tickets**: Cancel bookings when necessary.
- **View Available Trains**: Browse train schedules.
- **View Ticket Details**: See details of booked tickets.
- **View Personal Data**: Access and review personal information.
- **Change Password**: Update account password securely.

## Features

### 1. Input Validation
- **Password**: Minimum 8 characters, at least one number, and one alphabet.
- **CNIC**: Must be exactly 13 characters.
- **Name**: The first letter must be capitalized.
- **Employee ID**: Must start with "emp" to indicate an employee.
- **User ID**: Must not start with "emp" to differentiate from employees.

### 2. File Handling
- **User Data**: Managed in separate files for users and employees.
- **Train Data**: Stored in a dedicated file for schedules and routes.
- **Tickets Data**: Booked tickets are tracked in another file.

### 3. Guidance System
- **Input Validation**: Checks for all inputs to ensure correctness.
- **Guidance System**: Provides instructions for corrections.
- **Three-Attempt Rule**: After three invalid inputs, users return to the previous screen.

## Technologies Used
- **Programming Language**: C++
- **Concepts**: File Handling, User Authentication, Data Validation.

## How to Use
1. **Download**: Download the executable file from the provided source.
2. **Run the Executable**: Double-click the executable file to run the application.
3. **Login Credentials**: 
   - **Admin Username**: `admin`
   - **Admin Password**: `admin`
