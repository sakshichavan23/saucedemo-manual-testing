# SauceDemo Web Application — Manual Testing Project

## Overview
Beginner manual-testing practice project covering the login and logout flows of the SauceDemo demo application.

**Application:** https://www.saucedemo.com/

## Objective
Verify login behavior with valid and invalid inputs and check that logout returns the user to the login page.

## Scope
- TC01: Login with valid credentials
- TC02: Login with an invalid password
- TC03: Login with a blank username
- TC04: Login with a blank password
- TC05: Logout

## Test approach
Execute each test manually, compare the observed result with the expected result, and record Pass/Fail. Results in this initial report are based on the tester's observations and have not been independently verified.

## Summary of recorded results
| Test ID | Scenario | Recorded actual result | Status |
|---|---|---|---|
| TC01 | Valid login | Products page opened successfully | PASS |
| TC02 | Invalid password | Error appeared and login was rejected | PASS |
| TC03 | Blank username | Error appeared and login was rejected | PASS |
| TC04 | Blank password | Error appeared and login was rejected | PASS |
| TC05 | Logout | Login page appeared after logout | PASS |

Total recorded: 5 tests; 5 Pass; 0 Fail. This is limited to the five listed cases and does not establish that the whole application is defect-free.

## Files
- `Test-Cases.xlsx`: test cases and execution results
- `Test-Execution-Report.docx`: written report
- `Bug-Reports.md`: template for documenting defects

## Future improvements
- Add product sorting and cart tests
- Test checkout form validation
- Capture screenshots as evidence
- Track confirmed defects in Jira
- Record browser, operating system, date, and build/version used

## Disclaimer
This is a learning project using a public demo application. Do not use real personal data or attempt unauthorized testing of production systems.
