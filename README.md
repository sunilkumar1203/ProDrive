
# ProDrive - Car Rental System

## Overview

The Car Rental System is a Java console application that allows users to manage car rentals. It utilizes JDBC for database connectivity with Oracle and demonstrates various Object-Oriented Programming (OOP) principles and core Java concepts.

## Features

- **User Authentication**: Users can register and log in to the system.
- **Car Management**: Admins can add, update, and delete car listings.
- **Rental Management**: Users can view available cars and rent them.
- **Return Management**: Users can return rented cars and view rental history.
- **Search Functionality**: Users can search for cars based on various criteria (e.g., brand, type, price).
- **Data Persistence**: All data is stored in an Oracle database using JDBC.

## Technologies Used

- **Programming Language**: Java
- **Database**: Oracle
- **JDBC**: For database connectivity
- **OOP Concepts**: Inheritance, Polymorphism, Encapsulation, and Abstraction

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CarRentalSystem.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CarRentalSystem
   ```
3. Ensure you have the Oracle JDBC driver in your classpath.

4. Configure the database connection in your code.

## Usage

1. Compile the project:
   ```bash
   javac -cp .:path/to/ojdbc8.jar src/*.java -d bin
   ```
2. Run the main class:
   ```bash
   java -cp .:path/to/ojdbc8.jar bin/MainClass
   ```

## OOP Features Implemented

- **Classes and Objects**: The system is built using multiple classes such as `Car`, `User`, `Admin`, and `Rental`.
- **Inheritance**: The `Admin` class inherits from the `User` class.
- **Encapsulation**: Class fields are private and accessed via public methods.
- **Polymorphism**: Method overloading is used for different functionalities.
- **Abstraction**: Interfaces are used for defining common behaviors.

## Core Java Concepts Used

- **Data Structures**: Utilized collections for managing lists of cars and users.
- **Exception Handling**: Handled various exceptions that may occur during database operations.
- **Input/Output**: Used for reading user inputs and displaying results.


```

