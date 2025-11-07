
# Assignment 7 – Playwright Automation

## Project Overview
This project is part of my QA Internship tasks, focused on automating functional testing for the **Daraz.pk** website using **Playwright**.
The goal was to learn Playwright fundamentals, implement the **Page Object Model (POM)**, and perform real-world e-commerce testing including search, filters, and validation.

## Learning Objectives
- Understand Playwright test structure and syntax  
- Applied Page Object Model for scalable test design 
- Automate search and filter functionality on a live website  
- Validate product count and verify product details dynamically

## Tools & Technologies
- **Framework:** Playwright  
- **Language:** JavaScript  
- **Website Tested:** [https://www.daraz.pk/](https://www.daraz.pk/)  
- **Design Pattern:** Page Object Model (POM)
- **Reporting:** Playwright Test Runner, console logs, and screenshots

## Test Scenarios Automated
1. **Navigate to Daraz.pk**
   - Launch browser and handle optional cookie popup  

2. **Search Functionality**
   - Searches for the keyword “electronics” 

3. **Apply Brand Filter**
   - Applies the Philips brand filter on search results  

4. **Apply Price Filter (500–5000)**
   - Applies a price range filter to narrow results 

5. **Product Count Validation**
   - Count visible filtered products and verify the count is greater than 0  

6. **Open Product Details**
   - Click the first product from filtered results  

7. **Verify Free Shipping**
   - Check if “Free Shipping” label or text is available on product page

## Screenshots
### Test Results
![Terminal Test Results](screenshots/terminal_result.png)

### Browser Report
![Browser Report](screenshots/report.png)

### Test Run Video
![Test Run](screenshots/playwright_test_run.mp4)

## Notes
This assignment helped me understand real-world web automation using Playwright.
I learned how to use selectors, waits, and assertions effectively and structure code using Page Object Model (POM) for clean and reusable automation scripts.

## GitHub Repository
[https://github.com/2280138/Shine-Internship-Tasks](https://github.com/2280138/Shine-Internship-Tasks)