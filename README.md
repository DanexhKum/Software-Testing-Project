# BookCart Web Application Testing Project

## Project Overview
This project focuses on testing the BookCart web application, accessible at [https://bookcart.azurewebsites.net/](https://bookcart.azurewebsites.net/). The testing validates core functionalities such as user login, registration, book search, add-to-cart, and checkout, along with UI consistency and regression testing. The approach combines manual and automated testing, using Selenium WebDriver with Python for automation and PyTest for execution, as outlined in the test plan.

## Deliverables
1. **Test Plan Document** (`Test Plan Document for BookCart Web Application.pdf`)
   - Outlines the testing strategy, scope (functional, UI, regression testing), objectives, environment, tools, test types, and entry/exit criteria.
2. **Test Cases**
   - **Manual Test Cases** (`Test Cases.xlsx`): 50+ functional test cases in a table format (Test Case ID, Title, Steps, Expected Result, Actual Result, Status).
   - **Automation Test Cases** : Includes 15-20 test cases automated using Selenium, documented in a similar table structure.
3. **Automation Scripts** (`Automation_Test_Scripts/` directory)
   - Python-based Selenium WebDriver scripts for key user flows (e.g., registration, login, search).
   - Features proper locators, assertions, reusable functions, and setup/teardown logic.
4. **Execution and Bug Reports**
   - **Manual Execution Report** (`Manual_Evaluation_Report.xlsx`): Summarizes manual test execution results in a table format (Pass/Fail, Comments).
   - **Automation Execution Report** (`Automation_Evaluation_Report.pdf`): PyTest output detailing test results.
   - **Bug Report** (`Bug_Report.pdf`): Details bugs identified during testing (e.g., duplicate username registration, incorrect search results).
