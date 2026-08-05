# 🧪 SauceDemo Manual Testing Suite

## 📌 Project Overview
This repository contains a comprehensive **Manual Test Suite** executed for the [SauceDemo (Swag Labs)](https://www.saucedemo.com/) e-commerce web application. 

The goal of this project is to validate core functionalities, user workflows, boundary conditions, and UI responsiveness across the entire application lifecycle—from user authentication to complete checkout.

---

## 🛠️ Modules Tested
The test suite covers **25 Detailed Test Cases** across 7 primary functional modules:
1. **Authentication & Login:** Positive, negative, boundary, and error-user scenarios.
2. **Product Catalog & Sorting:** Item grid display, price filtering (Low to High / High to Low), and alphabetical sorting (A-Z / Z-A).
3. **Product Details:** Single item navigation, UI consistency, and cart additions from product views.
4. **Shopping Cart Management:** Dynamic badge updates, item removal, and persistent cart state.
5. **Checkout - Customer Information (Step 1):** Valid customer entries, mandatory field validations (missing zip code handling).
6. **Checkout - Overview & Calculations (Step 2):** Price verification, tax calculation logic, item subtotals, and transaction cancellation.
7. **Global Menu & Application State:** Session termination (logout) and clearing cart states via "Reset App State".

---

## 📄 File Structure
* `SauceDemo_Manual_Test_Suite_25.xlsx`: Formatted Excel sheet containing full Test Case IDs, Module tags, Step-by-step instructions, Expected vs. Actual Results, and Pass/Fail Execution Status.

---

## 📊 Sample Test Case Structure
| Test Case ID | Module | Scenario / Description | Expected Result | Status |
| :--- | :--- | :--- | :--- | :--- |
| **TC_LGN_001** | Authentication | Verify login with valid credentials | User lands on `/inventory.html` | `PASS` |
| **TC_CKO_005** | Checkout - Step 2 | Verify price calculations (Subtotal + Tax = Total) | Calculations match item sum exactly | `PASS` |

---

## 👤 Author
* **Vikas** – Aspiring QA / Software Testing Engineer
* **Core Skills:** Manual Testing, Functional Testing, Test Case Design, Defect Tracking, SQL, Java, Selenium.
