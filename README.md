![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)
# Apartment Reservation Database System

## Overview

This project presents the design and implementation of a **relational database system** built in `Oracle`, supporting apartment reservation management and customer data processing.

The solution was developed based on **business requirements analysis**, aiming to improve data organization, reduce errors, and support operational processes.

---

## Key Features

* Structured storage of:

  * reservations
  * apartments
  * customer data
* Ensured **data consistency** using relational constraints
* Support for **reservation management processes**
* Designed for **customer analysis and profiling**

---

## Database Design

The system was designed using a full modeling approach:

* **Conceptual model** – ERD (Chen notation)
* **Logical model** – structured data relationships
* **Relational model** – tables, keys, constraints
* **Physical model** – implemented in `Oracle` using CASE tools

---

## Process & System Modeling

### BPMN

* Modeled the process of apartment access after reservation
* Includes key retrieval flow and exception scenarios

### UML

* Use case diagrams describing system behavior
* Transformation analysis:

  * **AS-IS** – manual key handling
  * **TO-BE** – smart lock system (remote access via code)

---

## System Improvement (AS-IS → TO-BE)

* Eliminates manual key handling
* Introduces automated access via **smart lock system**
* Improves efficiency and user experience

---

## Technologies

* `Oracle Database`
* `SQL`
* `BPMN`
* `UML`
* CASE tools

---

## Skills Demonstrated

- **Database Design (End-to-End)**
  - Designed a complete relational database based on business requirements
  - Defined entities, relationships, and constraints
  - Implemented the database in `Oracle` with data integrity mechanisms

- **Data Modeling**
  - Created ERD using Chen notation
  - Developed logical and relational data models
  - Transformed business requirements into a normalized database structure
  
- **Business Analysis**
  - Identified business requirements and operational issues
  - Compared traditional vs automated access solutions (AS-IS → TO-BE)

- **Process Modeling (BPMN)**
  - Modeled apartment access workflow, including fallback scenarios
  - Defined interactions between client, owner, system, and security

- **System Modeling (UML & Data Modeling)**
  - Created use case diagrams for system functionality
  - Designed full database structure (ERD, logical, relational models)

---

## Purpose

Academic project based on a **real-world business scenario**, focused on designing a reliable and scalable database solution.

## Author

Created and maintained by:
- awie-dev (2025)
- GitHub: https://github.com/awie-dev

