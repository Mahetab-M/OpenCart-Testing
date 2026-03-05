# OpenCart-Testing
Manual QA Testing project for OpenCart e-commerce platform | 80+ test cases | 20 bugs identified | 15 modules covered
# OpenCart E-Commerce — Manual QA Testing Project

## 📋 Project Overview
Manual QA testing project for the OpenCart demo e-commerce platform, 
executed as a collaborative team effort simulating a real-world QA workflow.

## Test Summary
| Metric           | Result |
|------------------|--------|
| Total Test Cases | 80+    |
| Bugs Identified  | 20     |
| Modules Covered  | 15+    |
| Pass Rate        | 75%    |

## Modules Tested
**Customer Module (Mahetab Mohamed)**
- Registration & Login
- Account Management & Password Change
- Address Book (Add / Edit / Delete)
- Shopping Cart & Checkout
- Product Reviews & Ratings
- Search & Currency Change

**Admin Module (Hassan)**
- Admin Login & Dashboard
- Order Management
- Catalog & Categories
- Product Management

## Key Bugs Found
- Checkout failure — returns stock error instead of success message
- Input validation missing — numeric-only names accepted in registration and address fields
- Review and rating system non-functional — no action on submit
- Order management actions return error 404 (Update Status, Invoice, Add/Remove products)
- Admin permissions error — Delete, Rebuild, Add, and Edit categories blocked unexpectedly
- Account edit completes without feedback confirmation message

##  Tools Used
- **Test Management:** Microsoft Excel, Jira
- **Bug Tracking:** Jira
- **Version Control:** GitHub
- **Platform Tested:** OpenCart Demo

## Team
| Name | Module |
|------|--------|
| Mahetab Mohamed | Customer Module |
| Hassan | Admin Module |
