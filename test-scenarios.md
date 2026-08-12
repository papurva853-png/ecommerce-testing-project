# E-Commerce Website - Test Scenarios 🧪

This document contains test scenarios for the major modules of an e-commerce web application.

## 1. User Registration

| ID | Test Scenario |
|---|---|
| TS01 | Verify user can register with valid details |
| TS02 | Verify registration with an already registered email |
| TS03 | Verify registration with blank mandatory fields |
| TS04 | Verify email format validation |
| TS05 | Verify password validation |
| TS06 | Verify password confirmation |

## 2. User Login

| ID | Test Scenario |
|---|---|
| TS07 | Verify login with valid credentials |
| TS08 | Verify login with invalid username |
| TS09 | Verify login with invalid password |
| TS10 | Verify login with blank username |
| TS11 | Verify login with blank password |
| TS12 | Verify password masking |
| TS13 | Verify Forgot Password functionality |

## 3. Product Search

| ID | Test Scenario |
|---|---|
| TS14 | Verify search for an existing product |
| TS15 | Verify search for a non-existing product |
| TS16 | Verify search with blank input |
| TS17 | Verify search results are relevant |
| TS18 | Verify product sorting |
| TS19 | Verify product filtering |

## 4. Product Details

| ID | Test Scenario |
|---|---|
| TS20 | Verify product name |
| TS21 | Verify product price |
| TS22 | Verify product image |
| TS23 | Verify product description |
| TS24 | Verify product availability |
| TS25 | Verify product quantity selection |

## 5. Shopping Cart

| ID | Test Scenario |
|---|---|
| TS26 | Verify product can be added to cart |
| TS27 | Verify product can be removed from cart |
| TS28 | Verify product quantity can be increased |
| TS29 | Verify product quantity can be decreased |
| TS30 | Verify cart total |
| TS31 | Verify cart after adding multiple products |

## 6. Checkout

| ID | Test Scenario |
|---|---|
| TS32 | Verify user can proceed to checkout |
| TS33 | Verify shipping address |
| TS34 | Verify billing information |
| TS35 | Verify order summary |
| TS36 | Verify total order amount |
| TS37 | Verify required field validation |

## 7. Payment

| ID | Test Scenario |
|---|---|
| TS38 | Verify payment with valid details |
| TS39 | Verify payment with invalid details |
| TS40 | Verify payment failure handling |
| TS41 | Verify successful payment confirmation |
| TS42 | Verify order creation after successful payment |

## 8. Order Confirmation

| ID | Test Scenario |
|---|---|
| TS43 | Verify order confirmation message |
| TS44 | Verify order number |
| TS45 | Verify order details |
| TS46 | Verify order amount |
| TS47 | Verify order appears in order history |

## 9. Logout

| ID | Test Scenario |
|---|---|
| TS48 | Verify user can logout successfully |
| TS49 | Verify protected pages after logout |
| TS50 | Verify user is redirected to login after logout |

## Summary

| Module | Number of Scenarios |
|---|---:|
| Registration | 6 |
| Login | 7 |
| Product Search | 6 |
| Product Details | 6 |
| Shopping Cart | 6 |
| Checkout | 6 |
| Payment | 5 |
| Order Confirmation | 5 |
| Logout | 3 |
| **Total** | **50** |
