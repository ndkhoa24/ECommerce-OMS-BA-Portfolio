# Business Requirements Document (BRD)

## Multi-channel E-Commerce Management System

| Document Information | Details |
|---|---|
| Project Name | Multi-channel E-Commerce Management System |
| Document Type | Business Requirements Document |
| Version | 0.1 |
| Author | Nguyen Dang Khoa |
| Role | Business Analyst |
| Status | Draft |
| Date | August 10, 2026 |

> **Note:** This is a fictional business case created for portfolio and learning purposes.

---

# 1. Introduction

## 1.1 Project Background

ABC Retail is an e-commerce company that sells products through multiple sales channels, including its official website, Shopee, and TikTok Shop.

Currently, the company manages product information, customer information, orders, and inventory using separate Excel files and manual processes.

As the number of orders increases, the current approach has become inefficient and difficult to control. Data is fragmented across different files and sales channels, making it difficult for employees to track order status, maintain accurate inventory information, and generate business reports.

These limitations negatively affect daily operations, data accuracy, and management visibility.

The company therefore plans to develop a centralized **Multi-channel E-Commerce Management System** to improve operational efficiency and provide a single source of truth for sales-related information.

---

## 1.2 Business Problems

The current business process has several major problems:

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

The project aims to achieve the following business goals:

| ID | Business Goal |
|---|---|
| BG-01 | Centralize sales and order information across multiple sales channels. |
| BG-02 | Improve inventory visibility and accuracy. |
| BG-03 | Reduce manual effort in order processing and reporting. |
| BG-04 | Provide managers with centralized business performance information. |
| BG-05 | Improve the accuracy and consistency of operational data. |

Based on the identified business problems and goals, the company plans to develop a centralized **Multi-channel E-Commerce Management System** to improve operational efficiency and provide a single source of truth for sales-related information.

---

# 2. Project Objectives

The main objectives of the project are:

1. Provide a centralized platform for managing products, customers, orders, and inventory.
2. Enable employees to track and update order status efficiently.
3. Provide centralized inventory information across multiple sales channels.
4. Reduce manual data processing and Excel-based operations.
5. Provide dashboards and reports to support management decisions.
6. Improve data accuracy and operational transparency.
7. Establish role-based access to ensure users can only access functions relevant to their responsibilities.

---

# 3. Stakeholders

## 3.1 Stakeholder List

| Stakeholder | Role | Main Responsibilities / Needs |
|---|---|---|
| Sales Staff | Internal User | Create and manage customer orders. |
| Customer Service Staff | Internal User | View orders and support customer requests. |
| Warehouse Staff | Internal User | Manage inventory and fulfill orders. |
| Marketing Staff | Internal User | Manage promotions and vouchers. |
| Manager | Business User | Monitor sales performance and business reports. |
| System Administrator | System User | Manage users, roles, and system configuration. |
| Business Owner | Business Stakeholder | Monitor overall business performance and operational efficiency. |

---

# 4. Project Scope

## 4.1 In Scope

The initial version of the system will focus on the following major areas:

### Core Modules

- Product Management
- Customer Management
- Order Management
- Inventory Management
- Dashboard
- Reporting
- User and Role Management

### Supporting Modules

- Authentication and Authorization
- Voucher Management
- Shipping Management

The detailed functionality of each module will be defined during the subsequent requirement analysis phase.

---

## 4.2 Out of Scope

The following features are not included in the initial project scope:

- Development of a customer-facing e-commerce website.
- Development of native mobile applications.
- Direct integration with external payment gateways.
- Direct real-time integration with third-party shipping providers.
- Advanced AI-based demand forecasting.
- Automated accounting and tax management.
- Full ERP implementation.
- Advanced customer loyalty management.
- Marketing automation.

These features may be considered in future releases based on business priorities and available resources.

---

# 5. Assumptions

The project is based on the following assumptions:

1. Employees have access to the internal management system.
2. Each employee has an individual system account.
3. Users will be assigned appropriate roles and permissions.
4. Product and customer information is available for migration into the new system.
5. Sales channel data can be imported or synchronized with the system.
6. The company will provide the required business rules and operational policies.
7. Stakeholders will participate in requirement clarification and validation.
8. The initial version will focus on core internal business operations.

---

# 6. Constraints

The project may have the following constraints:

1. Limited development resources.
2. Limited project timeline.
3. Limited access to real e-commerce platform APIs.
4. External platform integrations may not be available during the initial implementation.
5. The initial version focuses on core operational workflows.
6. Some business requirements may require further clarification from stakeholders.
7. The project is developed as a portfolio case study and does not use real company data.

---

# 7. Success Metrics

The project will be considered successful when the following outcomes are achieved:

| ID | Success Metric |
|---|---|
| SM-01 | At least 90% of internal order-processing activities can be performed through the centralized system. |
| SM-02 | Employees can track the status of an order throughout the fulfillment process. |
| SM-03 | Inventory information is available from a centralized platform. |
| SM-04 | Managers can generate daily and monthly sales reports without manually consolidating multiple Excel files. |
| SM-05 | User access and system functions are controlled based on assigned roles and permissions. |
| SM-06 | Operational data can be accessed from a centralized system without relying on multiple independent Excel files. |

---

# Document Status

**Current Status:** Draft
