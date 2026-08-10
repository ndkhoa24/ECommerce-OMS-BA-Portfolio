#Business Requirements Document (BRD)

##Multi-channel E-Commerce Management System

| Document Information | Details |
|---|---|
| Project Name | Multi-channel Ecommerce Management System |
| Document Type | Business Requirements Document |
| Version | 1.0 |
| Author | Nguyen Dang Khoa |
| Role | Business Analyst |
| Status | Draft |
| Date | August 10, 2026 |

---

#1. Introduction

## 1.1 Project Background

ABC Retail is an e-commerce company that sells products through multiple sales channels, including its official website, Shopee, and TikTok Shop.

Currently, the company manages product information, customer information, orders, and inventory using separate Excel files and manual processes.

As the number of orders increases, the current approach has become inefficient and difficult to control. Data is fragmented across different files and sales channels, making it difficult for employees to track order status, maintain accurate inventory information, and generate business reports.

---

## 1.2 Business Problems

| ID | Business Problem |
|---|---|
| BP-01 | Order information is managed using multiple Excel files, increasing the risk of data loss and inconsistency. |
| BP-02 | Employees have limited visibility into the current status of orders. |
| BP-03 | Inventory information is not synchronized across different sales channels. |
| BP-04 | Revenue and sales reports require significant manual effort to consolidate. |
| BP-05 | Managers lack a centralized dashboard to monitor business performance. |
| BP-06 | Manual data entry increases the risk of human errors. |

---

## 1.3 Business Goals

| ID | Business Goal |
|---|---|
| BG-01 | Centralize sales and order information across multiple sales channels. |
| BG-02 | Improve inventory visibility and accuracy. |
| BG-03 | Reduce manual effort in order processing and reporting. |
| BG-04 | Provide managers with centralized business performance information. |
| BG-05 | Improve the accuracy and consistency of operational data. |
Therefore, the company plans to develop a centralized **Multi-channel E-Commerce Management System** to improve operational efficiency and provide a single source of truth for sales-related information.

---

# 2. Project Objectives

The main objectives of the project are:

1. Provide a centralized platform for managing products, customers, orders, and inventory.
2. Enable employees to track and update order status efficiently.
3. Provide centralized inventory information across sales channels.
4. Reduce manual data processing and Excel-based operations.
5. Provide dashboards and reports to support management decisions.
6. Improve data accuracy and operational transparency.

---

# 3. Stakeholders

| Stakeholder | Role | Main Responsibilities / Needs |
|---|---|---|
| Sales Staff | Internal User | Create and manage customer orders. |
| Customer Service Staff | Internal User | View orders and support customer requests. |
| Warehouse Staff | Internal User | Manage inventory and fulfill orders. |
| Marketing Staff | Internal User | Manage promotions and vouchers. |
| Manager | Business User | Monitor sales performance and business reports. |
| System Administrator | System User | Manage users, roles, and system configuration. |

---

# 4. Project Scope

## 4.1 In Scope

The system will include the following major modules:

- User Authentication and Authorization
- Dashboard
- Product Management
- Customer Management
- Order Management
- Inventory Management
- Voucher Management
- Shipping Management
- Reporting and Analytics
- User and Role Management

## 4.2 Out of Scope

The following features are not included in the initial version:

- Development of a customer-facing e-commerce website
- Development of native mobile applications
- Direct integration with external payment gateways
- Direct integration with third-party shipping providers
- Advanced AI-based demand forecasting
- Automated accounting and tax management

---

# 5. Assumptions

The project is based on the following assumptions:

- Employees have access to the internal management system.
- Product and customer information is available for migration into the new system.
- Sales channel data can be imported or synchronized with the system.
- Users have appropriate permissions based on their roles.
- The company will provide business rules and operational policies required for system implementation.

---

# 6. Constraints

The initial project may have the following constraints:

- Limited development resources.
- Limited project timeline.
- Initial integration with external platforms may be performed through data import instead of real-time APIs.
- The first version focuses on core order management and operational workflows.

---

# 7. Success Metrics

The project will be considered successful when:


| ID | Success Metric |
|---|---|
| SM-01 | Employees can manage orders from a centralized system. |
| SM-02 | Order status can be tracked throughout the fulfillment process. |
| SM-03 | Inventory information can be accessed from a centralized platform. |
| SM-04 | Management reports can be generated without manual consolidation from multiple Excel files. |
| SM-05 | Users can perform their assigned tasks according to their roles and permissions. |
