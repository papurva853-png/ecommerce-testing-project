# E-Commerce Website - Test Execution Report 🧪

## 1. Test Execution Overview

This document records the execution results of the manual test cases for the e-commerce web application.

Test cases will be executed manually and the actual results will be recorded based on the observed behavior of the application.

## 2. Test Environment

| Item | Details |
|---|---|
| Application | E-Commerce Web Application |
| Testing Type | Manual Testing |
| Browser | Google Chrome |
| Operating System | Windows |
| Tester | QA Tester |
| Test Environment | Web Browser |

## 3. Test Execution Status

| Test Case ID | Module | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC01 | Registration | Account should be created successfully | Pass
| TC02 | Registration | Validation messages should be displayed | Pass |
| TC03 | Registration | Email validation message should appear | Pass |
| TC04 | Login | User should login successfully | Pass |
| TC05 | Login | Error message should be displayed | Pass |
| TC06 | Login | Validation messages should appear | Pass |
| TC07 | Login | Password should be masked | Pass |
| TC08 | Product Search | Relevant products should be displayed | Pass |
| TC09 | Product Search | No product found message should appear | Fail |
| TC10 | Product Search | Appropriate result or validation should appear | Pass |
| TC11 | Product Details | Correct product name should be displayed | Pass |
| TC12 | Product Details | Correct product price should be displayed | Fail |
| TC13 | Product Details | Product image should be displayed correctly | Pass |
| TC14 | Product Details | Product description should be displayed | Pass |
| TC15 | Shopping Cart | Product should be added to cart | Pass |
| TC16 | Shopping Cart | Product should be removed | Pass |
| TC17 | Shopping Cart | Quantity and total should update correctly | Fail |
| TC18 | Shopping Cart | Total amount should be calculated correctly | Pass |
| TC19 | Checkout | Checkout page should open | Pass |
| TC20 | Checkout | Address should be accepted | Pass |
| TC21 | Checkout | Product, quantity and price should be correct | Pass |
| TC22 | Payment | Payment should be successful | Pass |
| TC23 | Payment | Appropriate payment error should appear | Pass |
| TC24 | Payment | Order confirmation should be displayed | Pass |
| TC25 | Order Confirmation | Confirmation message should be displayed | Pass |
| TC26 | Order Confirmation | Unique order number should be displayed | Blocked |
| TC27 | Order Confirmation | Correct product and amount should be displayed | Pass |
| TC28 | Logout | User should be logged out | Pass |
| TC29 | Logout | User should be redirected to login | Fail |

## 4. Status Definitions

- **Pass** — Actual result matches the expected result.
- **Fail** — Actual result does not match the expected result.
- **Blocked** — Test cannot be executed because of a dependency or environment issue.
- **Not Executed** — Test has not been executed yet.

## 5. Execution Summary

| Status | Count |
|---|---:|
| Pass | 24 |
| Fail | 4 |
| Blocked | 1 |
| Not Executed | 0 |
| **Total** | **29** |


