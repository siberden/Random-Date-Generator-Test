# Random-Date-Generator-Test
This repository includes test cases for validating a random date generator web app. The tests cover input validation, date generation, format customization, and error handling to ensure accurate and reliable date generation within specified ranges and formats.
Requirements
1 -Input Validation
The input field for “How many dates to generate?” should only accept positive integers.
The input field should not accept negative numbers or decimal values.
The start date and end date fields should accept valid date and time formats.
2 - Date Generation
The app should generate the specified number of random dates within the given range.
The generated dates should be unique and within the specified range.
The app should handle leap years correctly.
The app should generate the last day of the month correctly.
3 - Date Format
The app should support multiple date formats (for example :  MM-DD-YYYY, YY-MM-DD).
The custom date format should be configurable and correctly applied.
The app should handle custom date formats like “YYYY/MM/DD” correctly.
4 - Error Handling
The app should display appropriate error messages for invalid inputs.
The app should handle edge cases gracefully (for example : invalid date ranges, zero dates to generate).
Test Plan for Random Date Generator Web App
1. Introduction:
This test plan outlines the strategy, scope, objectives, and approach for testing the random date generator web application. The goal is to ensure the application functions correctly, handles inputs appropriately, and generates valid dates in the specified formats.

2. Objective:
To ensure the reliability, accuracy, and usability of the random date generator web application by validating its input handling, date generation logic, date format customization, and error handling mechanisms. The goal is to confirm that the application generates the correct number of unique, valid dates within specified ranges and formats, while appropriately handling invalid inputs and edge cases.
3. Scope
•	Functional testing of input fields, date generation logic, and date format customization.
•	Boundary value analysis and equivalence partitioning for input validation.
•	Error handling and edge case testing.
4. Test Items
•	Input field for “How many dates to generate?”
•	Start date and end date fields.
•	Date output format options (predefined and custom).
•	Generated dates.
5. Test Approach
•	Manual testing using predefined test cases.
•	Automated testing using Selenium, Junit, Cucumber and BDD approach regression testing.


