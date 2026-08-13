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

## 3. Test Execution Status

| Test Case ID | Module | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC01 | Registration | Account should be created successfully | Account was created successfully | Pass |
| TC02 | Registration | Validation messages should be displayed | Validation messages were displayed | Pass |
| TC03 | Registration | Email validation message should appear | Email validation message appeared | Pass |
| TC04 | Login | User should login successfully | User logged in successfully | Pass |
| TC05 | Login | Error message should be displayed | Error message was displayed | Pass |
| TC06 | Login | Validation messages should appear | Validation messages appeared | Pass |
| TC07 | Login | Password should be masked | Password was masked | Pass |
| TC08 | Product Search | Relevant products should be displayed | Relevant products were displayed | Pass |
| TC09 | Product Search | No product found message should appear | No product found message was displayed | Fail |
| TC10 | Product Search | Appropriate result or validation should appear | Appropriate result or validation was displayed | Pass |
| TC11 | Product Details | Correct product name should be displayed | Correct product name was displayed | Pass |
| TC12 | Product Details | Correct product price should be displayed | Product price did not match the expected result | Fail |
| TC13 | Product Details | Product image should be displayed correctly | Product image was displayed correctly | Pass |
| TC14 | Product Details | Product description should be displayed | Product description was displayed | Pass |
| TC15 | Shopping Cart | Product should be added to cart | Product was added to cart | Pass |
| TC16 | Shopping Cart | Product should be removed | Product was removed from cart | Pass |
| TC17 | Shopping Cart | Quantity and total should update correctly | Quantity and/or total did not update as expected | Fail |
| TC18 | Shopping Cart | Total amount should be calculated correctly | Total amount was calculated correctly | Pass |
| TC19 | Checkout | Checkout page should open | Checkout page opened successfully | Pass |
| TC20 | Checkout | Address should be accepted | Address was accepted successfully | Pass |
| TC21 | Checkout | Product, quantity and price should be correct | Product, quantity and price were correct | Pass |
| TC22 | Payment | Payment should be successful | Payment was successful | Pass |
| TC23 | Payment | Appropriate payment error should appear | Appropriate payment error was displayed | Pass |
| TC24 | Payment | Order confirmation should be displayed | Order confirmation was displayed | Pass |
| TC25 | Order Confirmation | Confirmation message should be displayed | Confirmation message was displayed | Pass |
| TC26 | Order Confirmation | Unique order number should be displayed | Test could not be completed because the required order number was unavailable | Blocked |
| TC27 | Order Confirmation | Correct product and amount should be displayed | Correct product and amount were displayed | Pass |
| TC28 | Logout | User should be logged out | User was logged out successfully | Pass |
| TC29 | Logout | User should be redirected to login | User was not redirected to the login page as expected | Fail |

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

## 6. Pass Percentage

**Pass Percentage = (Passed Test Cases / Total Test Cases) × 100**

**Pass Percentage = (24 / 29) × 100 = 82.76%**

## 7. Failed Test Cases

The following test cases failed during execution:

- **TC09** — Product Search
- **TC12** — Product Details / Product Price
- **TC17** — Shopping Cart / Quantity
- **TC29** — Logout / Protected Page

## 8. Blocked Test Cases

The following test case was blocked:

- **TC26** — Order Confirmation / Order Number

The test could not be completed because the required condition for verifying the order number was unavailable.

## 9. Conclusion

A total of 29 test cases were executed.

- 24 test cases passed.
- 4 test cases failed.
- 1 test case was blocked.
- No test cases remained unexecuted.

The overall pass percentage was **82.76%**.

The failed test cases require further investigation and defect reporting. The blocked test case should be executed again when the required functionality or test condition becomes available.
