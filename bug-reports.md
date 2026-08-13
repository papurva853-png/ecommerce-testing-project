# E-Commerce Website - Bug Reports 🐞

This document contains defects identified during manual testing of the e-commerce web application.

---

## BUG-001 — No Product Found Message Not Displayed

| Field | Details |
|---|---|
| Bug ID | BUG-001 |
| Test Case | TC09 |
| Title | No product found message is not displayed for unavailable product |
| Module | Product Search |
| Severity | Medium |
| Priority | Medium |
| Environment | Google Chrome / Windows |
| Preconditions | E-commerce website is accessible |
| Steps to Reproduce | 1. Open the website<br>2. Go to the product search field<br>3. Enter an unavailable product<br>4. Click Search |
| Expected Result | A clear "No product found" message should be displayed |
| Actual Result | Expected no-product message was not displayed |
| Status | Open |

---

## BUG-002 — Incorrect Product Price

| Field | Details |
|---|---|
| Bug ID | BUG-002 |
| Test Case | TC12 |
| Title | Product price does not match the expected price |
| Module | Product Details |
| Severity | High |
| Priority | High |
| Environment | Google Chrome / Windows |
| Preconditions | Product details page is accessible |
| Steps to Reproduce | 1. Open the website<br>2. Select a product<br>3. Open the product details page<br>4. Check the displayed price |
| Expected Result | Correct product price should be displayed |
| Actual Result | Product price did not match the expected result |
| Status | Open |

---

## BUG-003 — Cart Quantity Does Not Update Correctly

| Field | Details |
|---|---|
| Bug ID | BUG-003 |
| Test Case | TC17 |
| Title | Product quantity or total does not update correctly in shopping cart |
| Module | Shopping Cart |
| Severity | High |
| Priority | High |
| Environment | Google Chrome / Windows |
| Preconditions | A product has been added to the shopping cart |
| Steps to Reproduce | 1. Add a product to the cart<br>2. Open the shopping cart<br>3. Change the product quantity<br>4. Check the quantity and total amount |
| Expected Result | Product quantity and total amount should update correctly |
| Actual Result | Quantity and/or total did not update as expected |
| Status | Open |

---

## BUG-004 — User Not Redirected After Logout

| Field | Details |
|---|---|
| Bug ID | BUG-004 |
| Test Case | TC29 |
| Title | User is not redirected to login page after logout |
| Module | Logout / Authentication |
| Severity | High |
| Priority | High |
| Environment | Google Chrome / Windows |
| Preconditions | User is logged in |
| Steps to Reproduce | 1. Log in to the application<br>2. Navigate to the account/protected page<br>3. Click Logout<br>4. Try to access the protected page |
| Expected Result | User should be redirected to the login page and should not be able to access protected content |
| Actual Result | User was not redirected to the login page as expected |
| Status | Open |

---

## Bug Summary

| Bug ID | Test Case | Module | Severity | Priority | Status |
|---|---|---|---|---|---|
| BUG-001 | TC09 | Product Search | Medium | Medium | Open |
| BUG-002 | TC12 | Product Details | High | High | Open |
| BUG-003 | TC17 | Shopping Cart | High | High | Open |
| BUG-004 | TC29 | Logout | High | High | Open |

## Bug Statistics

| Severity | Count |
|---|---:|
| High | 3 |
| Medium | 1 |
| Low | 0 |
| **Total** | **4** |

## Conclusion

A total of four defects were identified during manual test execution.

Three defects were classified as High severity and one defect was classified as Medium severity.

All identified defects are currently marked as Open and require further investigation and resolution.
