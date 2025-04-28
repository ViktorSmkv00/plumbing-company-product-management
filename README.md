# Project Description: Plumbing Company Product Management (ServiceNow Application)

---

## Overview

The Plumbing Company Product Management application is a custom-built ServiceNow solution designed for a plumbing products company.  
It manages customer interactions, internal product development workflows, and quality feedback processes, all within a secure and easy-to-use system.

The project was developed in a clean, modular, and professional structure with role-based access control, Service Portal integration, and full automation.

---

## Key Features

- **Ticket Management:** Customers can submit support requests, incidents, product feedback, and order products directly from a user-friendly portal.
- **Task Automation:** Tasks are automatically created based on ticket types, approvals, and innovation flows.
- **Testing Management:** Internal and external testing tickets are managed separately with their own approval and task creation logic.
- **Innovation and Product Ideas:** Designers submit new product ideas, and innovators review and approve them through a voting mechanism.
- **Feedback Collection:** Feedback tasks are generated automatically for quality improvement after ticket closure (except admin/logistics tickets).
- **Scheduled Inactivity Monitoring:** Automatic notifications for tickets inactive over 48 hours to assigned users.
- **Custom Service Portal:** Clean customer-facing portal with big-button navigation (Submit Ticket, Order Product, View My Tickets).
- **Role-Based Access:** Full ACLs and role separation to ensure data security and proper functionality.
- **Flow Designer Automation:** All business processes automated using ServiceNow Flows and Scheduled Script Executions.

---

## Custom Tables

- **Ticket (x_1662488_pcpm_ticket)**
- **Task (x_1662488_pcpm_task)**
- **Product Idea (x_1662488_pcpm_product_idea)**
- **Product (x_1662488_pcpm_product)**
- **Customer (x_1662488_pcpm_customer)**

---

## User Roles and Responsibilities

| Role | Description |
|------|-------------|
| **Admin** | Full access to all tables, records, and administration. |
| **Customer** | Submit tickets, order products, and view their own tickets. |
| **Designer** | Submit new Product Ideas for innovation approval. |
| **Developer** | Handle tasks created from approved Product Ideas. |
| **Innovator** | Review and approve or reject Product Ideas (5 approvals needed). |
| **Support** | Manage, update, and close all submitted Tickets. |
| **Tester** | Submit internal and external testing tickets and follow testing approval flows. |

---

## Technologies Used

- **ServiceNow Washington Release**
- **Flow Designer**
- **Service Portal**
- **Record Producers**
- **Scheduled Script Executions**
- **ACL Security and Roles**

---

## Installation

The application can be imported via the included XML or ZIP file from the `/application_export` folder.

---

## Screenshots

Visual examples are available inside the `/screenshots/` folder.

---

## Future Enhancements (Optional)

- Create a dedicated Catalog Item for product ordering (future extension).
- Enhance Portal UI with dynamic elements like auto-filled product prices.
- Expand Feedback Task analysis and reporting.

---
