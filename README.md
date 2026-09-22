# OOP-Cpp-Unit-II

Student Name: Parth Bhupesh Lohi
PRN: 125UME1165
Class/Division: S.Y-C
Course Name: OOPs
Unit II

## List of programs

Real-Time Application 1: Employee Payroll System
Real-Time Application 2: Digital Payment Gateway
Real-Time Application 3: Vehicle Fleet Management

## Brief description of each program

### Program 01

👨‍💼 Employee Payroll System

A simple, object-oriented C++ program designed to manage different types of employees and calculate their salary based on their employment type.

🚀 Key Features

**Inheritance:** Uses a base `Employee` class with derived classes for `FullTimeEmployee`, `PartTimeEmployee`, and `Intern`.

**Protected Members:** Stores common employee information such as employee ID, name, and department using protected members.

**Hierarchical Inheritance:** Demonstrates multiple derived classes inheriting from a common base class.

**Constructor Chaining:** Demonstrates the execution of base and derived class constructors.

**Function Overriding:** Derived classes provide their own implementations for salary calculation.

**Abstract Class:** Uses an abstract base class to define common employee behavior.

📊 Sample Output

=== Employee Payroll System ===
Employee ID: E101 | Name: John | Type: Full-Time
Employee ID: E102 | Name: Alice | Type: Part-Time
Employee ID: E103 | Name: Rahul | Type: Intern

Salary details displayed according to employee type.

### Program 02

💳 Digital Payment Gateway

A simple, object-oriented C++ program designed to simulate different digital payment methods such as credit card, UPI, net banking, and wallet payments.

🚀 Key Features

**Abstract Class:** Uses an abstract `PaymentMethod` class to define common payment functionality.

**Pure Virtual Function:** Defines a common `processPayment()` function that is implemented by derived classes.

**Hierarchical Inheritance:** Uses multiple payment classes derived from the common `PaymentMethod` base class.

**Virtual Destructor:** Demonstrates the use of a virtual destructor in the base class.

**Runtime Polymorphism:** Allows different payment methods to be processed through a common interface.

📊 Sample Output

=== Digital Payment Gateway ===
Processing Credit Card Payment...
Processing UPI Payment...
Processing Net Banking Payment...
Processing Wallet Payment...

### Program 03

🚚 Vehicle Fleet Management

A simple, object-oriented C++ program designed to manage different types of vehicles used in a logistics company, including trucks, delivery vans, and bikes.

🚀 Key Features

**Inheritance:** Uses a base `Vehicle` class with derived classes `Truck`, `DeliveryVan`, and `Bike`.

**Protected Data:** Stores common vehicle information using protected data members.

**Hierarchical Inheritance:** Demonstrates multiple vehicle classes inheriting from a common base class.

**Function Overriding:** Each derived vehicle class provides its own implementation of vehicle-specific behavior.

**Virtual Functions:** Uses virtual functions to achieve runtime polymorphism.

📊 Sample Output

=== Vehicle Fleet Management ===
Vehicle: Truck | Registration No: TR101
Vehicle: Delivery Van | Registration No: DV102
Vehicle: Bike | Registration No: BK103

Vehicle details and specific information displayed for each vehicle.
