
# Task-03: Automated Login Test – SauceDemo

## Project Overview
This project demonstrates automated testing of the login functionality for a web application using Selenium WebDriver.
The demo site used for testing is SauceDemo.

Demo URL: https://www.saucedemo.com/

## Objective
To validate the login functionality by executing:
- Positive test cases (valid credentials)
- Negative test cases (invalid credentials, empty fields)

## Tools & Technologies
- Programming Language: Python
- Automation Tool: Selenium WebDriver
- Browser: Google Chrome
- Test Framework: unittest / pytest
- OS: Windows

## Test Scenarios Covered
1. Login with valid username and password
2. Login with invalid username
3. Login with invalid password
4. Login with empty username and password
5. Login with empty username
6. Login with empty password

## Valid Test Credentials (SauceDemo)
- Username: standard_user
- Password: secret_sauce

## Expected Result
- Valid credentials should redirect the user to the inventory page.
- Invalid or empty credentials should display appropriate error messages.

## Conclusion
All test cases were executed successfully. The login functionality behaves as expected for both positive and negative scenarios.
