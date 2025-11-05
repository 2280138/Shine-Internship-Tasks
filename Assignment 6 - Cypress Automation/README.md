# Assignment 6 – Cypress Automation

## Project Overview
This project is part of my QA Internship tasks, focused on automating web testing for the **SauceDemo** website using **Cypress**.  
The goal was to apply Cypress fundamentals, implement the **Page Object Model (POM)**, and use **custom commands** for reusable steps.

## Learning Objectives
- Understand Cypress test structure and syntax  
- Applied Page Object Model for better maintainability  
- Created reusable test steps with custom commands  
- Automated login functionality and product navigation scenarios

## Tools & Technologies
- **Framework:** Cypress  
- **Language:** JavaScript  
- **Website Tested:** [https://www.saucedemo.com/](https://www.saucedemo.com/)  
- **Reporting:** Cypress default test runner and screenshots  

## Test Scenarios Automated
1. **Login Success**
   - Valid credentials redirect to the inventory page  
   - Verifies visibility of product list  

2. **Login Failure**
   - Invalid credentials show proper error message  

3. **Product Navigation & Validation**
   - Logs in and navigates to product details page  
   - Verifies product name and price visibility  

## Screenshots
### Test Results
![Overall Test Results](screenshots/test_results.png)

### Login Success
![Login Success Result](screenshots/login_success_result.png)

### Login Failure
![Login Failure Result](screenshots/login_failure_result.png)

### Product Navigation
![Product Navigation Validation](screenshots/product_navigation&validation_result.png)

## Notes
This assignment enhanced my understanding of Cypress automation, the Page Object Model, and writing reusable, maintainable UI test cases.
It strengthened my confidence in structuring and executing real-world automated tests.

## GitHub Repository
[https://github.com/2280138/Shine-Internship-Tasks](https://github.com/2280138/Shine-Internship-Tasks)