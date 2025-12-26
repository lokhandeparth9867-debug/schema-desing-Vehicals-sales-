# 📊 SQL ER Diagram – Customer Order Management System

## 📌 Project Overview
This project demonstrates the design of a relational database using an SQL **Entity Relationship (ER) Diagram**. It models a real-world **Customer Order Management System**, where customers place orders for products. The database structure ensures data integrity, scalability, and efficient querying.

The project is ideal for beginners and aspiring **Data Analysts / SQL Developers** to understand database design, normalization, and relationships.

---

## 🗄️ Database Structure

### 1️⃣ Customers Table
Stores customer personal and contact information.

- CustomerId (Primary Key)
- FirstName
- LastName
- Email
- Country

---

### 2️⃣ Products Table
Stores product details and pricing information.

- ProductId (Primary Key)
- ProductName
- Category
- UnitPrice

---

### 3️⃣ Orders Table
Stores order transaction details and links customers with products.

- OrderId (Primary Key)
- OrderDate
- CustomerId (Foreign Key)
- ProductId (Foreign Key)
- Quantity

---

## 🔗 Relationships
- One customer can place **multiple orders**
- One product can appear in **multiple orders**
- Orders table acts as a bridge between Customers and Products

---

## 🔑 Key Concepts Used
- ER Diagram Design
- Primary Key & Foreign Key Constraints
- One-to-Many Relationships
- Relational Database Modeling
- SQL Data Normalization

---

## 🛠️ Tools & Technologies
- SQL
- ER Diagram
- Relational Database Design

---

## 🎯 Use Cases
- Customer order tracking
- Sales and product analysis
- Learning SQL joins and aggregations
- Database design practice for interviews

---

## 📄 Author
**Parth Lokhande**

---

## ⭐ How to Use
1. Create tables based on the ER diagram
2. Insert sample data
3. Perform JOIN and aggregation queries
4. Analyze customer orders and product sales

---

## 📌 Future Enhancements
- Add payment and shipment tables
- Implement indexes for performance
- Write advanced queries using CTEs and subqueries
