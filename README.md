# PR.5-Oop-Wrapper

# Employee Management System (OOP Based)

## 📌 Project Overview

This project is a **menu-driven Employee Management System** developed using **Object-Oriented Programming (OOP) concepts in Python**.
It demonstrates how real-world organizational roles like **Employee**, **Manager**, and **Developer** can be modeled using classes, inheritance, encapsulation, and polymorphism.

The system allows users to create different types of employees, display their details, compare salaries, and check class relationships through an interactive menu.

---

## 🎯 Objectives of the Project

* To understand **Object-Oriented Programming concepts**
* To implement **inheritance and method overriding**
* To apply **data encapsulation using access specifiers**
* To demonstrate **operator overloading**
* To build a **menu-driven application**

---

##  System Design (Conceptual)

### 1. Employee (Base Class)

The Employee class represents a generic employee and acts as the **parent class**.

**Key Responsibilities:**

* Store employee ID, name, age, and salary
* Protect sensitive data using encapsulation
* Provide controlled access to private data
* Display employee details
* Support comparison of employees based on salary

**Concepts Used:**

* Encapsulation (private attributes for ID and salary)
* Getter and setter methods
* Constructor and destructor
* Operator overloading for comparison
* String representation of objects

---

### 2. Manager (Child Class)

The Manager class represents employees with managerial roles.

**Key Responsibilities:**

* Inherit all properties of Employee
* Add department information
* Display both employee and department details

**Concepts Used:**

* Inheritance
* Method overriding
* Use of super keyword

---

### 3. Developer (Child Class)

The Developer class represents technical employees.

**Key Responsibilities:**

* Inherit all properties of Employee
* Store programming language specialization
* Display employee details along with programming language

**Concepts Used:**

* Inheritance
* Method overriding
* Specialization of parent class

---

## Encapsulation and Data Protection

* Employee ID and Salary are kept **private**
* Access is provided through **getter and setter methods**
* Salary validation ensures invalid values are not accepted

This ensures **data security and controlled modification**.

---

##  Operator Overloading

The system allows comparison of employees using:

* Greater than
* Less than
* Equal to

Employees are compared **based on their salary**, making it easy to determine who earns more.

---

##  Menu-Driven System

The application runs in a loop and provides options such as:

* Create Employee
* Create Manager
* Create Developer
* Display Employee Details
* Compare Salaries
* Check Subclass Relationship
* Exit Program

This design improves **user interaction and usability**.

##  Subclass Verification

The program verifies whether:

* Manager is a subclass of Employee
* Developer is a subclass of Employee

This confirms correct implementation of **inheritance**.


