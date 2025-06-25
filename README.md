This project was built as part of my DBMS coursework to demonstrate understanding of full CRUD operations and relational database design.

# Waste Management System – CRUD Web App

A Database Management System (DBMS) project built using **Flask**, **MySQL** and **HTML/CSS** to simulate a waste management portal for users, collectors, and admins.

## 🧾 Project Summary
This application allows:
- Citizens to register themselves and raise waste-related complaints.
- Admins to manage locations, assign waste collectors, and oversee collection.
- Collectors to view and resolve assigned tasks.

##  Key Functionalities
- 👤 User Registration
- 📍 Add & View Locations
- 🗑️ Assign Waste Bins
- 🧹 Register & Track Waste Collections
- 🙋 Report & Update Complaints
- 👷 Assign & View Collectors
- 📄 Full CRUD Support
- ✉️ Flash messages and error handling for better user feedback.
  
## ✅ Features
- User Registration: Add new users with form validation and store data in a relational database.
- Location Management: Add and view multiple locations with full relational support.
- Bin Assignment: Allocate bins to specific areas and manage their data.
- Collector Assignment: Assign collectors to manage bins and track collection.
- Complaint Tracking: Users can file complaints; admin can mark status as "Resolved".
- Waste Collection Records: Maintain history of collected waste with collector, location, and bin linkage.
- Data Display: Tabular views for all records (Users, Locations, Bins, Collectors, Collections, Complaints).

**CRUD Operations:**
- Create: Add data via registration forms
- Read: View data in styled tables
- Update: Edit complaint status from "Pending" to "Resolved"
- Delete: Remove records from database

Note: No separate login pages have been implemented for users, collectors, or admins.

