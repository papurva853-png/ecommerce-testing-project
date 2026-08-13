# E-Commerce Website - Test Summary Report 🧪

## 1. Project Overview

This project involved manual testing of an e-commerce web application.

The objective was to verify the major functionalities of the application, identify defects, execute test cases, and document the testing results.

---

## 2. Testing Scope

The following modules were tested:

- User Registration
- User Login
- Product Search
- Product Details
- Shopping Cart
- Checkout
- Payment
- Order Confirmation
- Logout

---

## 3. Testing Environment

| Item | Details |
|---|---|
| Application | E-Commerce Web Application |
| Testing Type | Manual Testing |
| Browser | Google Chrome |
| Operating System | Windows |
| Testing Method | Manual |
| Test Cases Executed | 29 |

---

## 4. Test Execution Summary

| Status | Count |
|---|---:|
| Pass | 24 |
| Fail | 4 |
| Blocked | 1 |
| Not Executed | 0 |
| **Total** | **29** |

---

## 5. Test Result Percentage

### Pass Percentage

**Pass Percentage = (Passed Test Cases / Total Test Cases) × 100**

**Pass Percentage = (24 / 29) × 100 = 82.76%**

### Fail Percentage

**Fail Percentage = (Failed Test Cases / Total Test Cases) × 100**

**Fail Percentage = (4 / 29) × 100 = 13.79%**

### Blocked Percentage

**Blocked Percentage = (Blocked Test Cases / Total Test Cases) × 100**

**Blocked Percentage = (1 / 29) × 100 = 3.45%**

---

## 6. Failed Test Cases

The following test cases failed during execution:

| Test Case ID | Module | Result |
|---|---|---|
| TC09 | Product Search | Fail |
| TC12 | Product Details | Fail |
| TC17 | Shopping Cart | Fail |
| TC29 | Logout | Fail |

---

## 7. Blocked Test Case

| Test Case ID | Module | Result |
|---|---|---|
| TC26 | Order Confirmation | Blocked |

The test could not be completed because the required condition for verifying the order number was unavailable.

---

## 8. Defects Identified

A total of **4 defects** were identified during testing.

| Bug ID | Test Case | Module | Severity | Priority | Status |
|---|---|---|---|---|---|
| BUG-001 | TC09 | Product Search | Medium | Medium | Open |
| BUG-002 | TC12 | Product Details | High | High | Open |
| BUG-003 | TC17 | Shopping Cart | High | High | Open |
| BUG-004 | TC29 | Logout | High | High | Open |

---

## 9. Defect Severity Summary

| Severity | Number of Defects |
|---|---:|
| High | 3 |
| Medium | 1 |
| Low | 0 |
| **Total** | **4** |

---

## 10. Testing Activities Performed

The following QA activities were performed:

- Test planning
- Test scenario identification
- Test case creation
- Manual test execution
- Pass/Fail analysis
- Defect identification
- Bug reporting
- Severity and priority classification
- Test execution documentation
- Test summary preparation

---

## 11. Key Findings

During testing, the following issues were identified:

1. The application did not display the expected message for an unavailable product search.
2. A product price did not match the expected result.
3. Shopping cart quantity or total did not update as expected.
4. Logout did not redirect the user to the login page as expected.
5. Order number verification could not be completed because the required condition was unavailable.

---

## 12. Overall Result

A total of **29 test cases** were executed.

- **24 test cases passed**
- **4 test cases failed**
- **1 test case was blocked**
- **0 test cases remained unexecuted**

The overall test pass percentage was **82.76%**.

Four defects were identified and documented.

---

## 13. Recommendation

The identified High severity defects should be investigated and fixed before considering the affected functionality ready for release.

After the defects are fixed:

1. Perform retesting of the failed test cases.
2. Perform regression testing on related functionality.
3. Re-execute the blocked test case when the required condition becomes available.
4. Update the defect status accordingly.

---

## 14. Conclusion

The manual testing project successfully demonstrated the complete QA testing process, from test planning and test case creation to execution, defect identification, and test reporting.

The project helped evaluate the functionality and reliability of the e-commerce application and documented the defects found during testing.

**Testing Result: 82.76% Pass**

**Total Defects Identified: 4**

**Overall Status: Testing Completed with Defects**
