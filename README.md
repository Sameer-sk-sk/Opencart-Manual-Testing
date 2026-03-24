# Opencart-Manual-Testing
# 🛒 OpenCart (Frontend) — Manual Testing Project

## 📌 Project Overview
This repository contains the complete manual testing documentation for the **OpenCart Frontend** e-commerce web application. I independently tested all major frontend functionalities including Register, Login, Search, Product Display, Cart, Checkout, and more — covering over 400 test cases across 31 test scenarios.

> **Application Under Test:** [OpenCart Demo](https://demo.opencart.com)
> **Type:** E-commerce Web Application (PHP + MySQL + Apache)

---

## 🗂️ Documents Included

| Document | Description |
|----------|-------------|
| `FRS.docx` | Functional Requirements Specification — defines all features of the OpenCart frontend |
| `Test_Plan.docx` | Test Plan — covers scope, objectives, strategy, roles, schedule, and risks |
| `Test_Scenarios.xlsx` | 31 Test Scenarios mapped to FRS requirements |
| `Test_Cases.xlsx` | Detailed test cases for all 31 scenarios |
| `RTM.xlsx` | Requirement Traceability Matrix — maps requirements to test scenarios and test cases |
| `Bug_Report.xlsx` | Bug report with 20 defects found during testing |
| `Login_Data.xlsx` | Test data used for login and related test cases |

---

## 🔍 Scope of Testing

### ✅ In Scope
- Register / Login / Logout
- Forgot Password
- Search
- Product Display Page
- Product Compare
- Add to Cart / Wish List / Shopping Cart
- Checkout
- My Account (Account Info, Change Password, Address Book)
- Order History, Downloads, Rewards, Transactions
- Newsletter, Contact Us, Gift Certificate
- Header, Menu, Footer
- Multi-currency functionality

### ❌ Out of Scope
- Database Testing
- API Testing
- Automation Testing

---

## 🧪 Test Summary

| Metric | Count |
|--------|-------|
| Total Test Scenarios | 31 |
| Total Test Cases | 400+ |
| Bugs Reported | 20 |
| Critical Bugs | 2 |
| Major Bugs | 8 |
| Minor Bugs | 10 |

---

## 🐛 Sample Bugs Found

| Bug ID | Summary | Severity |
|--------|---------|----------|
| OPEN_CART_BUG_1 | 'Thank you for registering' email not sent after account creation | Major |
| OPEN_CART_BUG_5 | User gets logged out on clicking browser back button | Critical |
| OPEN_CART_BUG_9 | User can login with old password after changing to new password | Critical |
| OPEN_CART_BUG_7 | No warning shown after 5 unsuccessful login attempts | Major |
| OPEN_CART_BUG_20 | Product not getting added to cart from wishlist | Critical |

---

## 🛠️ Tools Used

| Purpose | Tool |
|---------|------|
| Test Case Management | Microsoft Excel |
| Bug Tracking | Jira |
| Configuration Management | GitHub |
| Browsers Tested | Chrome, Firefox, Edge, Safari |
| OS | Windows 10 |

---

## 🗓️ Project Timeline

| Task | Date |
|------|------|
| FRS Document | 02 Jan 2026 |
| Test Planning | 03 Jan 2026 |
| Test Case Creation | 06 Jan – 14 Jan 2026 |
| Test Execution | Jan – Feb 2026 |
| Approval | 15 Feb 2026 |

---

## 👤 Author
**Sameer**
- Created: 31 Jan 2026
- Approved: 15 Feb 2026
