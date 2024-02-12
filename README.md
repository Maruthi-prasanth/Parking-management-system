<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parking Management System</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        h1 {
            color: #007BFF;
        }
        h2 {
            color: #28a745;
        }
        h3 {
            color: #dc3545;
        }
        p {
            margin-bottom: 15px;
        }
        code {
            background-color: #f8f9fa;
            padding: 2px 5px;
            border: 1px solid #d6d8db;
            border-radius: 4px;
        }
        pre {
            background-color: #f8f9fa;
            padding: 10px;
            border: 1px solid #d6d8db;
            border-radius: 4px;
        }
        ul {
            list-style-type: square;
            margin-bottom: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid #d6d8db;
            padding: 8px;
            text-align: left;
        }
    </style>
</head>
<body>

# Advanced Parking Management System

This Parking Management System is a console-based application written in C, designed to efficiently handle parking operations for cars, bikes, and autos. The system incorporates features such as vehicle parking, fee collection, receipt generation, and insightful displays of parked vehicles and earnings.

## Table of Contents

- [Features](#features)
- [Vehicle Fees](#vehicle-fees)
- [How to Use](#how-to-use)
  - [Compile and Run](#compile-and-run)
  - [Main Menu](#main-menu)
- [Advanced Usage](#advanced-usage)
- [Notes](#notes)

## Features

- **Vehicle Parking:** Park cars, bikes, and autos in designated slots.
- **Dynamic Slot Management:** Adjusts the availability of parking slots based on the type of vehicle.
- **Receipt Generation:** Generates a detailed receipt after successful parking transactions.
- **Data Persistence:** Utilizes structures and arrays to store customer details, providing seamless data retrieval.
- **Insightful Display:** View the total number of parked cars, bikes, autos, and overall earnings.
  
## Vehicle Fees

- **Car:** 300
- **Bike:** 100
- **Auto:** 150

## How to Use

### Compile and Run

1. **Compile and Run:** Use a C compiler to compile the code and execute the compiled executable.

### Main Menu

2. **Main Menu:**
    - **Option 1: Park Your Vehicle**
        - Choose the type of vehicle and input customer details.
        - Complete the payment process to receive a detailed receipt.
    - **Option 2: Check Your Vehicle**
        - Enter customer name and vehicle number to check if the vehicle is parked.
    - **Option 3: Display Number of Vehicles**
        - View the total number of cars, bikes, autos, and earnings.
    - **Option 4: Exit**
        - Quit the program.

## Advanced Usage

- **Structures and Arrays:** Data storage for customer details is efficiently managed using structures and arrays.
- **Dynamic Slot Allocation:** Parking slots dynamically adjust based on the availability of each vehicle type.
- **Input Validation:** Implements input validation loops to ensure accurate user input.
- **Clear Interface:** Utilizes `system("cls")` to create a clear and user-friendly interface.

## Notes

- This Parking Management System provides a foundation for a scalable and extensible parking solution.
- Modifications and enhancements can be made to suit specific requirements.

Feel free to leverage, enhance, and customize this Advanced Parking Management System to meet your unique needs. Contributions and improvements are always welcome!

</body>
</html>
