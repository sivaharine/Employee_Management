# Introduction

- This project is a simple Java-based Employee Management System.
- It is designed to manage employee details using core object-oriented programming concepts.
- The project contains different types of employees such as full-time employees, part-time employees, and contract employees.
- Each employee has common details like employee ID, employee name, department, and address.
- The project also handles salary calculation based on the type of employee.
- A full-time employee has a fixed monthly salary.
- A part-time employee salary is calculated using hours worked and hourly rate.
- A contract employee salary is calculated using the contract amount.
- The main purpose of this project is to show how Java classes, inheritance, abstraction, records, enums, collections, and service classes can be used together in a small application.

# Working

- The execution starts from the `EmployeeMgtApp` class.
- First, an `EmployeeService` object is created to manage employee operations.
- Then, an `Address` object is created and assigned to sample employees.
- The project creates sample employees using the `FullTimeEmployee`, `PartTimeEmployee`, and `ContractEmployee` classes.
- These employee objects are added to the employee list using the `addEmployee()` method.
- The `displayEmployees()` method displays employee details and their calculated salary.
- The `searchEmployeeById()` method searches for an employee using the employee ID.
- The `updateEmployeeDepartment()` method updates the department of an existing employee.
- The `calculateTotalSalary()` method calculates the total salary of all employees stored in the list.
- The `deleteEmployee()` method removes an employee from the list using the employee ID.
- The `Employee` class is an abstract sealed class, so only permitted employee types can extend it.
- The `calcSalary()` method is abstract in the `Employee` class and is overridden in each employee subclass.
- The `Department` enum is used to store fixed department values such as `IT`, `ADMIN`, `SALES`, and `HR`.
- The `Address` record is used to store city, state, and pincode in a simple way.
- The `ArrayList` inside `EmployeeService` stores all employee objects and performs operations on them.
