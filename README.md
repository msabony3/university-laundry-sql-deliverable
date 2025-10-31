**Overview**

This project was developed as part of a university Database Management Systems course. It simulates a laundry machine reservation system for student housing, allowing users to reserve washers and dryers, submit maintenance requests, and view operational analytics. The goal was to demonstrate how structured data, normalization, and SQL reporting can create an efficient scheduling and asset management platform similar to those used in real-world housing or facility management environments.

---
**Database Design**

The system is built around six normalized entities designed for referential integrity and clarity:

STUDENT – stores user information and login credentials

MACHINE – represents each washer and dryer, including operational details

RESERVATION – links students to scheduled machine times

BUILDING – organizes machines by physical location

MACHINE_TYPE – binary variable denoting machine type, either "Washer" or "Dryer"

MAINTENANCE_REQUEST – records issues, repairs, and resolution updates


Each table was designed with clear key relationships and constraints to maintain accuracy, consistency, and usability across the system.

---
**SQL**

I wrote SQL queries to support both administrative and user-facing insights, including:

-Current and historical reservations

-Machine utilization summaries by building and time frame

-Maintenance request tracking and completion rates

-Revenue summaries and user payment data

-Student activity analytics


These reports highlight joins, aggregations, subqueries, and views, illustrating how SQL logic can support real-world analytics and decision-making.

---
**Tools and Skills**

-MySQL

-Python (for query testing and data validation)

-Excel (for prototype reporting and early-stage analysis)

-Data modeling and normalization

-Entity-relationship design

---
