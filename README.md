# Restaurant Management System (MySQL)

This project is a *Restaurant Management Database System* built using *MySQL*.  
It efficiently manages restaurant operations such as reservations, orders, and menu items.

---

##  Project Overview

The system includes the following database functionalities:

- Manage *Menu Items, **Tables, **Customers, **Reservations, and **Orders*.
- Use *joins* to fetch combined information from multiple tables.
- Create *views* for reservation summaries.
- Use *subqueries* to find customers with spending above the average.
- Implement a *trigger* to automatically update table availability after a reservation.
- Use a *stored procedure* to count customer orders.

---

##  Database Schema

*Tables Created:*
1. MenuItems
2. Tables
3. Customers
4. Reservations
5. Orders
6. OrderDetails

Each table is related through *Primary Keys* and *Foreign Keys* ensuring referential integrity.

---

##  SQL Features Used

| Feature | Description |
|----------|-------------|
| *JOIN* | Combines data from Orders and Customers |
| *VIEW* | Displays combined reservation details |
| *SUBQUERY* | Finds customers who spent more than the average |
| *TRIGGER* | Automatically updates table availability after reservation |
| *STORED PROCEDURE* | Counts total orders per customer |

FROM Orders O
JOIN Customers C ON O.CustomerID = C.CustomerID;
