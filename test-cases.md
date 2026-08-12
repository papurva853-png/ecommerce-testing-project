# E-Commerce Website - Test Cases 🧪

This document contains detailed manual test cases for an e-commerce web application.

> **Note:** Actual Result and Status should be updated after executing the test cases on the application.

---

## 1. User Registration

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC01 | Register with valid details | Registration page is open | Enter valid details → Click Register | Valid name, email, password | Account should be created successfully | To be filled | Not Executed |
| TC02 | Register with blank mandatory fields | Registration page is open | Leave required fields blank → Click Register | Blank fields | Validation messages should be displayed | To be filled | Not Executed |
| TC03 | Invalid email format | Registration page is open | Enter invalid email → Submit | `abc@` | Email validation message should appear | To be filled | Not Executed |

---

## 2. Login

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC04 | Login with valid credentials | Registered account exists | Enter username and password → Click Login | Valid credentials | User should login successfully | To be filled | Not Executed |
| TC05 | Login with invalid password | Registered account exists | Enter valid username → Enter wrong password → Login | Wrong password | Error message should be displayed | To be filled | Not Executed |
| TC06 | Login with blank fields | Login page is open | Leave fields blank → Click Login | Blank username/password | Validation messages should appear | To be filled | Not Executed |
| TC07 | Verify password masking | Login page is open | Enter password | Password | Password should be masked | To be filled | Not Executed |

---

## 3. Product Search

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC08 | Search existing product | Website is open | Enter product name → Click Search | Existing product | Relevant products should be displayed | To be filled | Not Executed |
| TC09 | Search non-existing product | Website is open | Enter unavailable product → Search | `XYZ123` | No product found message should appear | To be filled | Not Executed |
| TC10 | Search with blank input | Website is open | Leave search field blank → Click Search | Blank | Appropriate result or validation should appear | To be filled | Not Executed |

---

## 4. Product Details

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC11 | Verify product name | Product page is open | Open product details | Available product | Correct product name should be displayed | To be filled | Not Executed |
| TC12 | Verify product price | Product page is open | Open product details | Available product | Correct product price should be displayed | To be filled | Not Executed |
| TC13 | Verify product image | Product page is open | Open product details | Available product | Product image should be displayed correctly | To be filled | Not Executed |
| TC14 | Verify product description | Product page is open | Open product details | Available product | Product description should be displayed | To be filled | Not Executed |

---

## 5. Shopping Cart

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC15 | Add product to cart | Product is available | Open product → Click Add to Cart | Available product | Product should be added to cart | To be filled | Not Executed |
| TC16 | Remove product from cart | Product is in cart | Open cart → Click Remove | Product in cart | Product should be removed | To be filled | Not Executed |
| TC17 | Increase quantity | Product is in cart | Increase quantity | Quantity = 2 | Quantity and total should update correctly | To be filled | Not Executed |
| TC18 | Verify cart total | Product is in cart | Open cart | Product price | Total amount should be calculated correctly | To be filled | Not Executed |

---

## 6. Checkout

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC19 | Proceed to checkout | Product is in cart | Open cart → Click Checkout | Valid cart | Checkout page should open | To be filled | Not Executed |
| TC20 | Verify shipping address | Checkout page is open | Enter valid address → Continue | Valid address | Address should be accepted | To be filled | Not Executed |
| TC21 | Verify order summary | Checkout page is open | Review order summary | Valid cart | Product, quantity and price should be correct | To be filled | Not Executed |

---

## 7. Payment

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC22 | Successful payment | Checkout is complete | Enter valid payment details → Pay | Valid test payment details | Payment should be successful | To be filled | Not Executed |
| TC23 | Invalid payment | Checkout is complete | Enter invalid payment details → Pay | Invalid test details | Appropriate payment error should appear | To be filled | Not Executed |
| TC24 | Payment confirmation | Payment is successful | Complete payment | Valid test payment | Order confirmation should be displayed | To be filled | Not Executed |

> **Note:** Do not use real card numbers or real financial information. Use only test/sandbox payment details when a website provides them.

---

## 8. Order Confirmation

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC25 | Verify order confirmation | Order is successfully placed | Complete an order | Valid test order | Confirmation message should be displayed | To be filled | Not Executed |
| TC26 | Verify order number | Order is successfully placed | Check confirmation page | Valid test order | Unique order number should be displayed | To be filled | Not Executed |
| TC27 | Verify order details | Order is successfully placed | Open order details | Valid test order | Correct product and amount should be displayed | To be filled | Not Executed |

---

## 9. Logout

| Test Case ID | Scenario | Preconditions | Test Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC28 | Logout successfully | User is logged in | Click Logout | Logged-in user | User should be logged out | To be filled | Not Executed |
| TC29 | Access protected page after logout | User has logged out | Try to access account page | Logged-out user | User should be redirected to login | To be filled | Not Executed |

---

## Test Case Summary

| Module | Test Cases |
|---|---:|
| Registration | 3 |
| Login | 4 |
| Product Search | 3 |
| Product Details | 4 |
| Shopping Cart | 4 |
| Checkout | 3 |
| Payment | 3 |
| Order Confirmation | 3 |
| Logout | 2 |
| **Total** | **29** |

## Status Definitions

- **Pass** — Actual result matches expected result.
- **Fail** — Actual result does not match expected result.
- **Blocked** — Test cannot be executed because of a dependency or environment issue.
- **Not Executed** — Test has not been executed yet.
