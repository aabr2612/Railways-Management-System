# Railways Management System

## Project Overview
  The **Railways Management System** is a console-based application developed using **C++**. This system is developed to manage various requirements of railway operations, including train schedules, ticket bookings, and user management. The system supports three types of users: **Admin**, **Employee**, and **Passenger**, each with different roles and access.

The purpose of this project is to demonstrate programming fundamentals, including user authentication, data validation, file handling, basic system management, and the use of parallel arrays.

## Features

### 1. **User Roles & Functionalities**

#### Admin
  - **User Management**: Admin can manage both employee and passenger data (add, delete, update, search, and view all).
  - **Train Management**: Admin has the ability to add, remove, and view train routes.
  - **Ticket Management**: Admin can view details of booked tickets, calculate revenue, and manage bookings.
  - **Statistics**: Admin can view statistics like the total number of tickets booked and total revenue.

#### Employee
  - **User Management**: Employees can add, delete, update, search, and view passenger data.
  - **Train Management**: Employees can manage train routes by adding or removing them.
  - **Ticket Management**: Employees can book or cancel tickets for passengers and view booked tickets.
  - **Personal Data**: Employees can view and update their own data, including changing their password.

#### Passenger
  - **Ticket Management**: Passengers can book and cancel tickets. They can also view their booking details.
  - **Train Information**: Passengers can view the available train schedules.
  - **Personal Data**: Passengers can view and update their own information, including changing their password.

### 2. **Input Validation**
  - **Password Validation**: Ensures that passwords are at least 8 characters long and contain both numbers and letters.
  - **CNIC Validation**: CNIC must be exactly 13 characters long.
  - **Employee and User ID**: Employee IDs start with "emp" and user IDs do not, ensuring clear differentiation between roles.
  - **Name Validation**: Ensures the first letter of names is capitalized to maintain consistency.

### 3. **File Handling**
  - **Data Storage**: User data (passenger and employee) is stored in separate files, ensuring that information can be easily retrieved and updated.
  - **Train Data**: Train schedules and routes are stored in their own file, allowing easy access and modifications.
  - **Ticket Data**: Booked ticket details are maintained in a separate file to track passenger reservations and related data.

### 4. **Guidance System**
  - The system provides guidance and error messages for user inputs, helping users use application and correct mistakes.
  - If an invalid input is made three times in a row, the system returns to the previous screen, ensuring user-friendly operation.

## Technologies Used
  - **Programming Language**: C++

## Data Structures
  - **Parallel Arrays**: This system uses **parallel arrays** to store related data, such as:
    - **Train Data**: Arrays are used to store details such as train numbers, route information, and ticket prices.
    - **User Data**: Arrays store passenger and employee details like IDs, names, and passwords.
    - **Ticket Data**: Arrays are used to store booking information, such as passenger IDs, train numbers, and booking statuses.

Using parallel arrays allows for a simple and efficient way to store and manage data.

## How to Use
**Clone the Repository**:
   - Clone the repository to your local machine using Git:
     ```bash
     git clone https://github.com/aabr2612/Railways-Management-System.git
     ```
   - Run the Executable: Double-click to launch the program.
          Login using the following credentials:
            - **Admin Username**: `admin`
            - **Admin Password**: `admin`

Once logged in, users can access the functionalities based on their role (Admin, Employee, or Passenger).

## Conclusion
  **Railways Management System** is a C++ console application that manages train schedules, ticket bookings, and user information. It uses basic C++ features such as file handling, data validation, and user authentication. The system is divided into three user roles i.e., Admin, Employee, and Passenger, each with different functionalities and access.