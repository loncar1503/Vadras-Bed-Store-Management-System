# Vadras-Bed-Store-Management-System

# Vadras – Bed Store Management System

## Overview

Vadras is a business-oriented software system designed to support daily operations in a bed retail company with multiple physical store locations.  
The system is intended for real-world use in a production environment and is actively developed as a practical business solution.

This repository provides a **high-level overview and architectural description** of the system.  
The actual application source code is maintained in a **private repository** due to its commercial nature and real-world usage.

---

## System Architecture

The system follows a **client–server architecture**:

- **Windows Forms Desktop Application**  
  Used by store employees for daily operations such as creating orders, managing products, and reviewing order data.

- **ASP.NET Core Web API**  
  Serves as the central backend layer, handling business logic, validation, and data access.

- **SQL Server Database**  
  Stores all persistent data, including products, orders, order items, and related business information.

All desktop clients communicate exclusively with the API, ensuring centralized data access and consistency across all store locations.

## Core Functionality

- Centralized order management across multiple retail locations  
- Product and order item handling  
- Order status tracking  
- Customer and delivery-related data storage  
- Clear separation between user interface, business logic, and data access layers  

The system is designed to be extensible and maintainable, while the desktop client prioritizes efficiency and ease of use for everyday business operations.

---

## Project Structure

The solution is organized using a layered architecture:

- **Domain Layer** – Core business entities and domain models  
- **API Layer** – ASP.NET Core Web API using Entity Framework Core  
- **Client Layer** – Windows Forms desktop application  

This structure supports long-term scalability and clean separation of responsibilities.

