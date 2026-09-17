# Justdial Website – Manual Testing Project

## Project Overview

This project contains manual testing documentation prepared for the Justdial website.

The objective of this project is to validate important website functionalities such as business search, location handling, filters, business listings, contact actions, reviews, authentication, navigation, responsive behavior, and negative test scenarios.

## Testing Type

* Manual Functional Testing
* UI/UX Testing
* Negative Testing
* Location-based Testing
* Basic Performance Testing
* Regression-oriented Test Coverage

## Modules Tested

* Business Search
* Location Selection
* Current Location Detection
* Location Permission Handling
* Business Listings
* Business Details
* Rating Filter
* Category Filter
* Sorting
* Call / Contact
* Map / Directions
* Ratings & Reviews
* Login / Authentication
* Responsive Design
* Search Loading
* Special Character Handling
* Back Navigation

## Test Execution Summary

| Status           | Count |
| ---------------- | ----: |
| Pass             |    19 |
| Fail             |     1 |
| Blocked          |     0 |
| Total Test Cases |    20 |

## Defect Identified

### JD-DEF-001 – Sorting and Location Relevance

While testing the Friendly Rating sorting option, the results were sorted successfully, but the displayed businesses were from different areas across Chennai rather than being restricted to the tester's nearby/current locality.

The issue has been documented in the Defect Log for further requirement confirmation.

## Repository Contents

```text
Test_Documentation/
└── Justdial_Manual_Test_Report_Updated.xlsx
```

The Excel workbook contains:

* Detailed Test Cases
* Actual Results
* Expected Results
* Test Status
* Priority
* Severity
* Defect ID
* Remarks
* Test Scenario Coverage
* Execution Summary
* Defect Log

## Testing Approach

The test cases were executed by providing different search inputs, changing locations, applying filters, validating business information, checking navigation and contact actions, and performing negative-input testing.

Actual observations were recorded in the test execution report.

## Author

**Ramya R**

**212223230169**

B.Tech – Artificial Intelligence and Data Science
