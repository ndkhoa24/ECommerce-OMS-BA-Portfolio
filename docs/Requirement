# System Requirements

## Multi-channel E-Commerce Management System

| Document Information | Details                                    |
| -------------------- | ------------------------------------------ |
| Project Name         | Multi-channel E-Commerce Management System |
| Document Type        | Requirements Specification                 |
| Version              | 0.1                                        |
| Author               | Nguyen Dang Khoa                           |
| Role                 | Business Analyst                           |
| Status               | Draft                                      |

---

# 1. Purpose

This document defines the stakeholder and functional requirements for the Multi-channel E-Commerce Management System.

The system aims to centralize product, customer, order, and inventory information to reduce manual processes, improve data accuracy, and provide better visibility into daily e-commerce operations.

---

# 2. Stakeholder Requirements

## 2.1 Sales Staff

Sales Staff need a centralized system to:

* View and search customer information.
* Create new customer orders.
* View order details.
* Track the current status of orders.
* Search and filter orders.
* View product availability before creating an order.

## 2.2 Customer Service Staff

Customer Service Staff need the ability to:

* Search for customers.
* View customer order history.
* View the current status of customer orders.
* Update customer information when authorized.
* Handle customer requests related to orders.
* Record order-related issues.

## 2.3 Warehouse Staff

Warehouse Staff need the ability to:

* View orders that require fulfillment.
* Check product availability.
* View current inventory levels.
* Update order fulfillment status.
* Record stock-in and stock-out transactions.
* View inventory movement history.

## 2.4 Manager

Managers need the ability to:

* View business performance through a dashboard.
* Monitor total orders.
* Monitor order status.
* Monitor sales performance.
* View revenue reports.
* Monitor inventory levels.
* Identify low-stock products.

## 2.5 System Administrator

System Administrators need the ability to:

* Create user accounts.
* Update user information.
* Activate or deactivate user accounts.
* Assign roles to users.
* Manage system permissions.

---

# 3. Functional Requirements

## 3.1 Product Management

### FR-P01 — Create Product

The system shall allow authorized users to create a new product.

The product information shall include:

* Product ID
* Product Name
* Category
* SKU
* Price
* Stock Quantity
* Product Status

### Acceptance Criteria

* The system shall generate or assign a unique Product ID.
* Product Name is required.
* SKU must be unique.
* Price must be greater than zero.
* Stock Quantity cannot be negative.
* The product shall be successfully saved when all required information is valid.

---

### FR-P02 — View Product

The system shall allow authorized users to view product information.

The product list shall display:

* Product ID
* Product Name
* SKU
* Category
* Price
* Stock Quantity
* Status

---

### FR-P03 — Search Product

The system shall allow authorized users to search for products.

Users shall be able to search by:

* Product Name
* SKU
* Category

---

### FR-P04 — Update Product

The system shall allow authorized users to update product information.

Users may update:

* Product Name
* Category
* Price
* Product Status

Inventory quantity changes shall be managed through the Inventory Management module.

---

### FR-P05 — Deactivate Product

The system shall allow authorized users to deactivate a product.

A deactivated product:

* Shall remain available for historical records.
* Cannot be added to new orders.
* Shall not be permanently deleted from the system.

---

# 3.2 Customer Management

### FR-C01 — Create Customer

The system shall allow authorized users to create a customer record.

Customer information shall include:

* Customer ID
* Full Name
* Phone Number
* Email
* Address
* Customer Status

### Acceptance Criteria

* Full Name is required.
* Phone Number is required.
* Phone Number must follow a valid format.
* Customer ID must be unique.

---

### FR-C02 — View Customer

The system shall allow authorized users to view customer information.

---

### FR-C03 — Search Customer

The system shall allow authorized users to search for customers by:

* Customer Name
* Phone Number
* Email

---

### FR-C04 — Update Customer

The system shall allow authorized users to update customer information.

---

### FR-C05 — View Customer Order History

The system shall allow authorized users to view the order history of a selected customer.

The order history shall include:

* Order ID
* Order Date
* Order Status
* Total Amount

---

# 3.3 Order Management

### FR-O01 — Create Order

The system shall allow authorized users to create a new customer order.

An order shall include:

* Order ID
* Customer Information
* Order Items
* Product Quantity
* Unit Price
* Total Amount
* Sales Channel
* Order Status
* Order Date

### Acceptance Criteria

* An order must contain at least one product.
* The customer must be identified before the order can be created.
* Product quantity must be greater than zero.
* The system shall calculate the total amount automatically.
* The system shall assign a unique Order ID.
* The order shall record its creation date and time.

---

### FR-O02 — View Order

The system shall allow authorized users to view order details.

Order details shall include:

* Order ID
* Customer Information
* Order Items
* Order Quantity
* Total Amount
* Sales Channel
* Order Status
* Order Date

---

### FR-O03 — Search and Filter Orders

The system shall allow authorized users to search and filter orders.

Users shall be able to filter orders by:

* Order ID
* Customer
* Order Status
* Sales Channel
* Order Date

---

### FR-O04 — Update Order Status

The system shall allow authorized users to update the order status according to their assigned permissions.

The initial order statuses are:

* Pending
* Confirmed
* Processing
* Shipped
* Delivered
* Completed
* Cancelled

The system shall record the status change history.

---

### FR-O05 — Cancel Order

The system shall allow authorized users to cancel an order.

When an order is cancelled:

* The cancellation reason shall be recorded.
* The order status shall be changed to `Cancelled`.
* The cancellation action shall be recorded in the order history.

---

# 4. Non-Functional Requirements

## NFR-01 — Performance

The system should return search results within 3 seconds under normal operating conditions.

## NFR-02 — Security

Users shall only access functions and data based on their assigned roles and permissions.

## NFR-03 — Data Integrity

The system shall prevent duplicate unique identifiers and invalid data.

## NFR-04 — Usability

The system should provide a simple and consistent user interface for internal users.

## NFR-05 — Auditability

The system shall maintain history records for important activities, including order status changes and inventory adjustments.

---

# 5. Open Issues

The following items require further clarification from stakeholders:

| ID    | Open Issue                                                          | Status |
| ----- | ------------------------------------------------------------------- | ------ |
| OI-01 | How will product data be synchronized with external sales channels? | Open   |
| OI-02 | At which order status should inventory be deducted?                 | Open   |
| OI-03 | Which user roles are allowed to cancel an order?                    | Open   |
| OI-04 | Can a completed order be modified?                                  | Open   |
| OI-05 | What information is required for an order to be considered valid?   | Open   |

---

# 6. Requirement Summary

| Module              | Number of Requirements |
| ------------------- | ---------------------: |
| Product Management  |                      5 |
| Customer Management |                      5 |
| Order Management    |                      5 |
| **Total**           |                 **15** |

