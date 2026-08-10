# Web Application QA Testing Portfolio

## Overview

This repository demonstrates a structured manual QA testing approach for a modern web application.

The objective is to validate application functionality, usability, input validation, navigation, responsive behavior, and cross-browser compatibility while documenting defects in a clear and reproducible format.

This project demonstrates practical QA activities that can be applied to web applications, SaaS platforms, e-commerce applications, financial applications, and other customer-facing products.

## Testing Approach

The testing process follows these major stages:

1. Requirement analysis
2. Test planning
3. Test scenario identification
4. Test case creation
5. Functional testing
6. Exploratory testing
7. UI and usability testing
8. Form and validation testing
9. Responsive testing
10. Cross-browser testing
11. Defect reporting
12. Regression testing
13. Test summary and final reporting

## Testing Areas

### Functional Testing

* Application navigation
* User registration
* Login/logout
* Form submission
* Buttons and links
* Page workflows
* Data validation
* Error handling

### UI Testing

* Layout consistency
* Text alignment
* Buttons and controls
* Fonts and spacing
* Images and icons
* Visibility of UI elements

### Usability Testing

* Ease of navigation
* Clarity of instructions
* User feedback and error messages
* Consistency of workflows
* Overall user experience

### Responsive Testing

Testing across:

* Desktop
* Tablet
* Mobile

Different viewport sizes are used to identify layout problems, overlapping elements, horizontal scrolling, and inaccessible controls.

### Cross-Browser Testing

Testing may include:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## Defect Reporting

Each defect is documented with:

* Bug ID
* Title
* Environment
* Preconditions
* Steps to reproduce
* Expected result
* Actual result
* Severity
* Priority
* Evidence/screenshots
* Status

## Example Test Result

| Test ID | Scenario           | Expected Result               | Result |
| ------- | ------------------ | ----------------------------- | ------ |
| TC-001  | Open application   | Homepage loads successfully   | PASS   |
| TC-002  | Submit empty form  | Validation messages displayed | PASS   |
| TC-003  | Invalid email      | Email validation displayed    | PASS   |
| TC-004  | Click support link | Support page opens            | PASS   |
| TC-005  | Mobile viewport    | Layout adapts correctly       | FAIL   |

## Example Defect

**BUG-001 — Mobile navigation overlaps page content**

**Severity:** Medium

**Steps to reproduce:**

1. Open the application on a mobile viewport.
2. Navigate to the home page.
3. Open the navigation menu.
4. Scroll down the page.

**Expected Result:**

Navigation should remain usable without overlapping important page content.

**Actual Result:**

The navigation menu overlaps the main content and partially hides the page heading.

**Evidence:**

Screenshot attached to the bug report.

## Testing Principles

The testing approach emphasizes:

* Accuracy
* Reproducibility
* Risk-based testing
* Clear documentation
* User-focused validation
* Thoroughness
* Effective communication

## Tools

Typical tools used in this type of testing include:

* Google Chrome DevTools
* Microsoft Edge DevTools
* Firefox Developer Tools
* Postman
* GitHub
* Jira / similar issue trackers
* Google Sheets / Excel
* Browser responsive testing tools

## Disclaimer

This repository is a demonstration QA portfolio project. No confidential client information, proprietary source code, credentials, or production data is included.
